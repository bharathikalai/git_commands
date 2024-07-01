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


# command 8 

## git fetch and git pull

follow command 7 so that you will understand the concept
story: one of your team met working on you branch and push his changes to the repo now you want to know what are the changes ha made 
if you use git pull your team met changes will merge  to your local repo you just know to see his changes and no need to merge his changes to your local repo you go with git fetch command
when you do git fetch command git repo latest changes will be stored your local repo but it wont merge with your local repo instead
you can see the changes if you do git pull all the latest changes will be merge your local repo i hope you understand the concept still 
you dont understand please do practice

![alt text](image-7.png)

# command 9 

## git log 

please follow command 8 :  one of your team met made some changes in your branch and commit the changes and push it to the git repo 
you asked your team met hay team_met_name  what are the commits you made yesterday he said this that like that now i am thinking if git 
provide any event tracking command that would be very helpfull for us : yes git has the solution that is git log
using git log you can view all the commits 

# command 10

## git reflog

please follow command 9 : i am working on my branch and made lots of commits and add files and delete i did a many action : can i track my actions :  yes you can using git reflog  you can list your git history  
# note:you cant list others action history
![alt text](image-8.png)

# command 11

## git diff 
uncommit changes you can see by using this command
example: if you have made changes locally  want to check what changes you have made you can use git riff command to view the changes
![alt text](image-9.png)

# command 12

## git reset --soft HEAD~1
## git reset --hard HEAD~1

head is nothing but latest commit
~1 mean one step back 
:by using this command you can revert the commit :
![alt text](image-10.png)
![alt text](image-11.png)


# command 13 
## git revert  commit_id or git checkout commit_id 

example : First, you had Hello World.
Then, you mistakenly changed it to Hello Mars.
Finally, you fixed it back to Hello World.

The git revert command helps you fix mistakes while keeping a record of everything that happened.
![alt text](image-12.png)


# command 14

## git blame file_name
# Shows what revision and author last modified each line of a file.

![alt text](image-13.png)


# command 15

## git show commit_id

# The git show command in Git is used to display various types of objects and information, such as:

Commits: It shows the details of a specific commit, including the commit message, author, date, and the changes introduced in that commit.
Tags: It can display the details of a specific tag.
Trees: It can show the contents of a tree object, similar to the output of git ls-tree.
Blobs: It can show the contents of a blob object, similar to the output of git cat-file -p.
![alt text](image-14.png)


# command 16

## git archive --format=zip HEAD > abc.zip

# by uing this command we can create a zip file with all our git repo file and folders 

![alt text](image-15.png)


# command 17 

## git config --global user.name "your name"
## git config --global user.email "your mail id"

# the purpose of this command is to set a repo user name 


# command 18

## git clean
using this command you can remove the untracked file for your local repo


# command 19
## git rebase branch_name


# command 20 
## git stash
## git stash pop


# command 21
##  git cherry-pick commit_id


# command 22
## git bisect start
## git bisect bad
## git bisect good commit_id

# git rebase
