## important command :
# command 1:

## git init ## 

when you use this command git will create a new folder ( .git ) 
why we need this folder when we do any action in git(add or commit and delete) these logs will be stored in this repo
![alt text](image.png)

# use ls -a command to view this folder

# command 2:
## git add . ## 

this command is for add the new file into the staging
# what is staging
there is a three stage our goal is to deploy our files to the git hub repository so we need to follow this first git add and second git commit and third is git push
i have created a folder called git add inside the folder i have added a file called gitadd.txt now i need to add my to the git 
staging for that i am using git add command  still you not understand okey simple example: 
you are running a grocery shop  which is git  you need to show case some items which is file i hope you understand this is the first  stage  once you added the file by using git add command then you need to verify what are the files added in staging how??
its very simple by using git status command you can verfiy the changes which you made.
## command : git status
![alt text](image-1.png)



# command 3:
## git commit -m "write about the changes" ##
m is nothing but message, if you do any changes in file or add a new file by using -m you can describe the changes
okey we know what is git add now what is git commit ? if you follow the command 2 you will understand still you not understand
example:   i have grocery shop i showcase the item(git add ) now one of our customer came to our shop and bought  iteams and but still that iteam is in the store why because that customer bought everthing so he cant keep : okey comming to the git commit the git commit also the same  when you add any file into the staging that file will be stored in your local now when you do git commit you are telling to the git that i am lock this file this file is going to the git hub repo i hope you understand the concept : coming to our storying that customer told me that hay bharathi i will send some to collect these items. 

![alt text](image-2.png)


# command 4:

## git push origin -u branch name

please follow command 1 so that you will understand the concept : coming to the topic now that customer driver came to my shop and he said hay bro customer name sent to pick his stuff i replied (git push origin -u branch_name) 
what it mean :  already my file stored in staging 1 now i am telling to the git hay git this is file i need to put it in my git
repo so i am locking the file with message (grocery concept locking the items ) this is staging 2 commit 
git push is staging 3  now that driver deliver those items to the end user or customer :  git repo i hope you understand the concept

![alt text](image-3.png)

# command 5 

## git branch 

what is git branch ? why we need this ? 
as you all know what is git ? git is a version control application where developer work together and store their code 
story : i am creating a application called food_app its kind or food delivery application i am woking on specfic module like specfic page (home page) my team mets also working on different pages so if everyone working in same branch it will be very defficult to manage their add and commit and push so they need  different branch by using git branch command you can list the all branchs

![alt text](image-4.png)

# command 6

## git branch branch_name  or git branch checkout -b branch_name

follow command 5 so that you will understand the concept 
story: every developers ask me to create a new branch in git so i used this command(git branch ) to create a new branch for them 
story: i have created a new branch for my team mets now  they  asking me bro i want to move to my new branch how to do  i replied please read command 7 
![alt text](image-5.png)

# command 7

## git checkout branch_name

follow command 6 so that you will understand the concept
story: by using this command (git checkout branch_name) you can move to your branch
![alt text](image-6.png)

abc