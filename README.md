<!-- initialize empty git repo -->

1- git init

add everything in the folder to the repo

2- git add .

status of whether files are added to the repo or new files and stuff

git status

shows list of commits and who did them

git log

Commit changes that were added to the repo ,one liner

3- git commit -m "Message here"

what branch am i on

4- git branch

list of branches

git branch

create a new branch

5- git branch "a new branch"

go to the new brach

git checkout "a new branch"

go back to the master branch

git checkout master

now make an empty repository in github, then copy it's link

link the github repo you just created to your git repo by adding it as origin, now your github repo is the remote origin of your git repo

6- git remote add origin "Your Github repo's URL"

if origin already exists you can remove it with `git remote remove origin`

you can also see your remotes with `remotes -v` 

you can rename the branch with `git branch -M $someName`

To realy put this repo on github now, you will 'Push' the desired branch to the remote

7- git push -u origin main    


