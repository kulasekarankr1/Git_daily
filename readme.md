Hi Guys this is the Git and GitHub learning session in the step by step for understand

" HI macha epdi irruka "
## This is in bug branch made some changes to check whether it is branched

## This names is new bug branch and this is the branch of new bug derived from the main file
## is it all going fine?

zero to Adavance learning class
git is used for sharing the project with the team to note individual changes

git is used for project sharing 
1. different part of workers
2. no need to mention what are the changes have been made to make a note of changes . so 

3. Repository - folder
4. .git - hidden folder (used to track the code , what are the changes has made 
5.commit - used to have snapshot , idhu varaikum panadhellam podhum lock panni vichukum
6. commit message - eg. darkmode i was working , so it will remember what are the changes we had changed int eh commit 
as a text
7. main Branch -> another branch (branch cutting) -> MTB123 ticket name 
8. Git - was created by LInux starworld , 
9. What is Git and Github -> 
the tool that handles the version and tool is git . 
GitHUB is the cloud platform is used to store the cloud . using the git only we can store the github.


                                Git Commnads
## A. commands 

1.The command to find the username is " git config user.name "
2. To find the mail id attached  - > "git config  user.email "
3. To find the list fo files -> git config --list
4. ssh -T git@github.com


## B.Setting the username, email Command

1. git config --global user.name 'gitname'
2. git config --global user.email 'gmail'

## C.Repository comands - create a repository in the hub
(This is one time commands to create a branch)

1. git config  --global init.defaultBranch main
2 git init
(created the empty repository)

## D. post work after creating the folder and files 

1. git status - will provides name of the which branch we are working on , what are the things we have commited , untracked file.

2. git add " give the name of the file" - if its done you can see the changes the U symbol will be changed to 'A'.

3. git commit -m 'give the message what you want to mention'
it will create a id for changes below

4. git log - will provide the what are the changes we made

5.  git add . - it will show the what add the remaining file which not get added . 

## E.Get into the Previous work

If i want to see the previous command and changes i have made or Switch to the previous without affecting the main branch i can use this command.

1. git log - in this copy the commit line id which you want to view
2. git checkout 'paste the id here' - here it comes to the end of the work.

so you  it will shows previous file has created 

3. git checkout main - it will comeback to the main folder 

4. git checkout -f main - This command is used to remove the change and wants to continue to the current folder where you were in like(Eg. you have made changes in the file and saved it change to 'M' symbol - modified . so if you want to currently want to remove the change 2 ways are there
1. you can directly enter the folder and delete the changes you made 
2. Another is that above method which will revert and delete the new changes have been made(discarded)

so theses and all we done in the laptop is Git . where we made changes and get back the previous file and all. 


When we want to share this to our Team Mates or others  we use GitHub. 
                                      
##                                 GitHub>
## 1.create repository ->name of the repository -> towards click create a repository 

Commands:
1.git remote add origin "http is provided copy and paste here"
2. git branch -M main
3. git push -u origin main

after these steps it will ask the sigin page do the necessary

                           
##                                     BRANCHES

1.If we are working with 2 to people we all cant work in the same  Main or if we want to add some extra feature . we should cut out the from main branch. 

## commands in vs terminal

1. git branch bug - create a branch named bug
2. git checkout bug - only if we checkout from the branch only we can make changes- it will come like (switched to branch bug)
(optional)
3. git checkout -b feature - (short cut method to create another branch named feature)

the feature branch will be created under bug . because it was created under bug.

to prove that some changes made into featrure branch in the readme  file

## make the changes in readme fileand do below
1. git add .
2. git commit -m 'This is the message what you updated'
3. git push origin main
## If this is the first push for the branch:
4. git push -u origin main
5. git status
6. git checkout main - it again come to the main branch

(git checkout 'branchname without quotes'- is used to switch the  branches)

## if we want to create a branch into another branch so we this command

1." git branch bug2 bug "  -( bug2 is new branch name) bug is old branch name [ this command implies in wherever branch u were in).

So these changes were done in the local laptop and git. 
 
## TO reflect the changes in the github follow these commands                  
##                              COMMANDS
## To update the changes in already exisiting branch use this commnad:

1. git push --set-upstream  origin "branch name to push"
2. git checkout feature
3. git push -u origin - "U" for upstream

##                                  MERGE THE CHANGES

so in GitHub the changes in the branches will be there. To merge the things in the main branch you can compare & merge option 

1. feature + main = compare and pull -> Add a title 
Description - this has the new feature
2. Merge to pull request 
3. pull request can be viewed by . then merge it 

pull request ->new pull request -> select the branches what you want to merger and do that


To find the new branches " git fetch"


##                                Merge conflicts

1.git checkout  new
2. if you cant match the 