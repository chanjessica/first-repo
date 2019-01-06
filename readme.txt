it's easier to do :
git clone https://github.com/chanjessica/first-repo

git clone https://github.com/username/username.github.io
git clone https://github.com/ilvhk2/HappyBowl.git

cd username.github.io
echo "Hello World" > index.html

git init
# run once in a given directory --> tell Git to keep track of changes to this directory

git add
# add a file --> tell Git to track the current state of it   (staging) - can be staged multiple times before it is committed.
# making a snapshot of this file

git commit
# a record of changes made to staged file(s), not the whole file(s)
# it tack who and when changes were committed
# make a permanent record from all the snapshots

---
git add --all

git commit -m "Initial commit"

git push -u origin master

----

cd ../..
cd Git

git --version
git status
git config
git config -a
git config --system
git config --list

git config --global user.name "ilvhk2"
git config --global user.email "ilvhk2@yahoo.com"
git config --list
git config user.name

git init
tree .git

ls -l *.html
git add *.html
git commit -m 'initial project version'
git push origin master

git remote add origin https://github.com/ilvhk2/R
git status
git pull

git remote add origin https://github.com/ilvhk2/R
git branch -a
git remote remove origin
git remote add origin https://github.com/ilvhk2/R

git pull origin master
git push -u origin master

rm -rf .git

git clone https://github.com/ilvhk2/R
git add .
git status
git commit -m 'initial project version'
git push origin master

git pull origin master
git add Unix
git commit -m 'added a folder with files'
git push -u origin master

mkdir .ssh
ls -la ~/.ssh
----  C:\Users\jc\.ssh

ssh-keygen -t rsa -b 4096 -C "ilvhk2@yahoo.com"
eval $(ssh-agent -s)
ssh-add ~/.ssh/id_rsa
ls -la ~/.ssh
clip < ~/.ssh/id_rsa.pub

git config --global
git status

cd /c/_UWClass/HTML100/first-repo
git config --global user.name "chanjessica"
git config --global user.name
git config --global user.email "jchan_sea@yahoo.com"
git config user.email
git init

git remote add origin https://github.com/chanjessica/first-repo.git
git remote -v
git push origin master

touch file.txt
git add file.txt
git commit -m "testing"

git push -u origin master
git config user.name
ssh -vT chanjessica@github.com
ssh -vT git@github.com
ssh -vT git@github.com
ssh-add -l
eval "$(ssh-agent -s)"
ssh-add -l
ssh-add -l -E md5


-- search myDoc.html in a repository to find the line you want to edit
git grep -n 'myDoc.html$'
-- jump to the beginning of that line


--- ATOM with EMMET --- https://docs.emmet.io/cheat-sheet/
ul>li*5>a.social    [tab]
(ul>li*5>a.social)+span	[tab]
(ul>li*5>a.social)+footer [tab]

---


new to Atom Editor. question - how to open atom terminal so I can type in command?

Ctrl + \ => tree view

Ctrl + Shift + p  => open the command palatte
Ctrl + ,		  => open Settings
	change Porject Home Default from C:\Users\jc\github to C:\_UWclass\HTML100

Ctrl + o 		  => open file
Ctrl + Shift + A  => open project folder

Ctrl + t|p	=> open a file in a Project

Ctrl + S => SAVE
Ctrl + Shift + S => SAVE AS


=== atom command line ====
--open html100 and css100 directories at the same time
> atom ./html100 ./css100

-- search myDoc.html in a repository to find the line you want to edit
> git grep -n 'myResume$'
-- e.g return \_UWclass\HTML100\myDoc.html:84:#### myResume
-- jump to the beginning of that line
> atom \_UWclass\HTML100\myDoc.html:84

> git grep -n --column 'myResume'
-- e.g return \_UWclass\HTML100\myDoc.html:84:62
-- jump to the exact column of that line
> atom \_UWclass\HTML100\myDoc.html:84:62

--======  multi select
click
hold the CTRL key
