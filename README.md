# formation_git
éléments de support de la formation du 19/11/2025


------------------------------------------------------------------------
This is the project README file. Here, you should describe your project.
Tell the reader (someone who does not know anything about this project)
all they need to know. The comments should usually include at least:
------------------------------------------------------------------------

- PROJECT TITLE:
- PURPOSE OF PROJECT: 
- VERSION or DATE: 
- HOW TO START THIS PROJECT:
- AUTHORS: 




- USER INSTRUCTIONS:

# how to pull request in github 

**To make our work easier, please use the following tuto, DON'T PUSH ANYTHING IN MASTER(MAIN) WITHOUT A PULL REQUEST**

It will help us track the changes, the one who did it and avoid conflicts. So folow me step by step and don't hesitate to ask question in the comments section or on Whatsapp :wink: 


## step 1 : create a issue on github
[clic here to create a issue on github ](https://github.com/Noemie-U/formation_git/issues/new)

Under development section (at right) you find the link "create a branch" in blue. A new modal appears, just submit it!


## step 2 : commit your changes 
In your local repository (in github or your terminal) you will write 
```
git checkout master
git pull
```

On your terminal, the new branch is listed `* [new branch] le-nom-de-la-branche-qui-est-enfaite-le-titre-de-ton-isssue 
` 

Then do checkout to switch to the new branch : 
```
git checkout le-nom-de-la-branche-qui-est-enfaite-le-titre-de-ton-isssue 
```

Do your stuff; make your change and check it with : 
```
git status 
```

To aprouve your changes do ( **don't forget the space and the point after add**) :
```
git add .
git status  #to check if everything is ok 
```
After that, commit your changes to save it in local and comment :
```
git commit -a -m "my best comment"
```
You can commit as many time as you want.

To finish this step, push your local changes on github with :  
```
git push
```
(you don't need to pull because only one persone is working  the branch !!)


## step 3 : creat pull request on github

Go on github on the main page `<Code>` you will see a banner the suggest to create the pull request.


Submit your pull request, don't forget to add the reviewer, to assign yourself, choose  or create the label.

And last but not least you wait (or not) for the reviewrs to approve the pull request before clicking on "Merge pull request" button.
