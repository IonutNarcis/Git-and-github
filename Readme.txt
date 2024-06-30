Error makes cleaver


Git is a version control system 
It is used to store the version and history of the project
Manipulate files with the command
The history of adding and deleting files is stored in another file known as the git repository
It is used to collaborate with the code
Github is a web based git repository hosting service - uses the git as the backbone
commit message is very important


command
1. git config --global user.name "name"
   git config --global user.email "enter the regis email"
2. git clone
   clone the repo in the local repo






Steps to connect them both
1. git config --global user.name "name"
   git config --global user.email "enter the regis email"
2. Create a folder in the desktop and open terminal in visual studio code
3. Open the folder and give "git clone"
4. go to code and copy the link and paste near git clone "link paste here"
5. After cloning now the git repo is in the local file. give cd filename and enter into it


Create a file in local and send it to the git repo
6. in step 5 u have entered into the folder and now u r going to create a file in there 
7. check the git status once
8. Note
When we clone the git repo to local, there are two sections called the git copy folder and the local folder
9. so when u check the git statu, since it is present in the local system u get that the files are untracked 
10. git add newfile.txt
11. git status 
12. when i added the newfile --> it now moves from the local to the imaginary staging area
13. git commit -m "message"
14. Now the file in the imaginary staging area comes to the git copy folder but now reflect in the github
15. git push origin main
there may be sign in here for the  first time
16.insert - addd - commit - push

Write some code in the file 
1. do the same procedure of adding files in the repository


Deleting a file in the local and reflect the same in the github repository
1. first delete the file in the github
2. again do
git add test3.txt
git commit -m "deleted test3.txt file"
git push origin main
now the file will be deleted in the github


Create a file in the github write it there and pull it
1.dummy.txt create in github
2.git pull enter 
3. modification - add- commit-push


create a folder and push 
1. create a folder
have html file
2. cd enter into the folder
inside it has the html file
change it into git repository git init
3. now git file inside the folder
4. git add . 
5. commit
but the destination is not clear
6. git push origin main
7. git remote add origin " "
git branch
8. git push origin master
9. we can also change the name of the branch
10.git branch -M main
git status 
add 
commit
git push origin main


Branches
git branch -a


1. go to github and create a new branch there in
2. the beanch created in the remote repo is not visible in the local so git pull
3. git branch -a
now visible
4.switcing between branches
5.git checkout branchname
now u can again add files as usual
when push the file 
git push origin new branch


git diff  @ main 
this give the difference 
git merge newbranch
git push origin main



pull request
1. create a new branch in the command line
git branch newbranch
git branch -a
git checkout newbranch
check again if needed
not reflect in the github
create a file in the new branch 
git add .
git commit -m "" 
git push origin  newbranch

now present in github

u cannot merge the information as u wish in the industry u can give the pull requst to the main branch

go to pull request
go to the new branch
create a pull request
and give it 
boss will look at it and allow u to merge

CONFLICT
1. two member trying to change the same file
2. the boss seeing the pull request and seeing the conflict anda= it can be manuslly solver by resolve conflict by manual edit
3. git get confused when same files are being changes


