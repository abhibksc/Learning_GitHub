Freshers install first-- git base or git GUI; then____

****************************Configuring Git**************************************
i am tell to git , inwhich account i am going to changing the files.
configure the username and email id by which we could commit changes in github by the help of git; that's why we install the git base and git GUI;

to configure git

git config --global user.name "My Name"
git config --global user.email "someone@email.com"

git config --list (to verify)



git clone:

1.> Copies a repository from a remote server to your local machine.

git clone <repository_url>



2.> git status:

Shows the status of changes as untracked, modified, or staged.

git status


four things that shows.. 

a>. if new files that git doesn't yet track 
(untracked) still not commited

b.> changed 
(modified) commited hogaya

c.> staged
(file is ready to be commited)

d.> unmodified
(unchanged)

3.> Add:

adds new or changed files in your working directory to the Git Staging area.

git add<- file name->

4.> Commit:

It is the record of change

git commit -m "some message"



5.> Push Command:

Push - upload local repo content to remote repo

git push origin main

6.> git init 

The git init command is used to initialize a new Git repository.
This initializes a new Git repository in the current directory. After running git init, you'll see a message indicating that an empty Git repository has been initialized.

****************************REPOSITORY**************************************

I want to make a particular folder or repo to a git repo.. there commands___

git init
git remote add origin <--link-->
git remote -v (to verify remote)
git branch (to check branch )
git branch -M main (to rename branch)
git push origin main

****************************Branch**************************************

I want to make new branch in github
git checkout -b <-new branch name->  (to create new Branch)

i want to delete current branch;
first i want to change the branch then give command__

git branch -d <-branch name->  (to delete branch)

i want to change the current branch to another branch;

git checkout<-another branch name->

i want to rename the current branch

git branch -M main (to rename branch)

i want to check the current branch name ;

git branch (to check branch)




