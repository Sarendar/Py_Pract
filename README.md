# Py_Pract
Practicing on github account 
$ git clone https://github.com/Sarendar/Py_Pract.git
$ git status
$ git branch
$ git add test_one.py

#to initial username and password
$ git init
$ git config user.name "sarendar"
$ git config user.email "sarender.vennapureddy@gmail.com"


$ git commit -m 'first version of test task' .
$ git log
$ git push

#Remove uncommeted changes for all the files using below command.
$ git checkout -- .

#revert commeted changes
$ git revert f1e8e6f476324c73fdf72bf5375e54927b410805

#Revert the code upto git add
$ git revert -n d556306b4f49712e1de88198211647ac5367e302

#reset all reverted code from file.
$ git reset --hard d556306b4f49712e1de88198211647ac5367e302

#create new branch called development
$ git branch development

#checkout to other branch
$ git checkout development