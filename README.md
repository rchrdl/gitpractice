# README
==========

Github Practice
Learning how to use Git using command-line

1. git init
2. create txt file
3. git status
4. git add file.txt (to track) OR git add -A (to add all files to staging area / track all files)
5. git commit -m "Message for the commit"
6. git remote add origin "https://github.com/rchrdl/reponame.git"
7. git push -u origin master


### Notes
To open file
- vim "filename"

To save and close:
- esc
- :x

close commit vim screen:
- :wq


$ git diff (show the changes)
$ git status
$ git add -A
$ git status
$ git commit -m "Message"
$ git pull origin master (pull any changes that have been made since the last time that we pulled from the repository, just to make sure it's up-to-date)
$ git push origin master (push to master branch)

### Add .gitignore
$ touch .gitignore
open .gitignoore file with a text editor and add files we want to ignore: *.log
$ git add -A
$ git commit -m "Added ignore file"

### Branches
$ git branch branch-name
$ git branch (show all the branches / branch names)
$ git checkout branch-name (move to this branch)
make changes in the files in this branch then:
$ git status
$ git add -A
$ git commit -m "Message"

### Push Branch to Remote Repository
$git push -u origin branchname (the -u will associate the branchname so next time we pull and push we just call git pull and git pull)
$git branch -A

### Merge
Merge branch
$ git checkout master (go to master branch)
$ git pull origin master
$ git branch --merged (check the branches that we've merged in so far)
$ git merge branchname
$ git push origin master

### Delete Branch
$ git branch (first make sure the branch is merged)
$ git branch -d branchname

### Dlete Branch from the Remote Repository
$ git push origin --delete branchname