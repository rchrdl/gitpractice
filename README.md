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
1. $ git status
2. $ git add -A
3. $ git status
4. $ git commit -m "Message"
5. $ git pull origin master (pull any changes that have been made since the last time that we pulled from the repository, just to make sure it's up-to-date)
6. $ git push origin master (push to master branch)

### Add .gitignore
1. $ touch .gitignore
2. open .gitignoore file with a text editor and add files we want to ignore: *.log
3. $ git add -A
4. $ git commit -m "Added ignore file"

### Branches
1. $ git branch branch-name
2. $ git branch (show all the branches / branch names)
3. $ git checkout branch-name (move to this branch)
4. make changes in the files in this branch then:
5. $ git status
6. $ git add -A
7. $ git commit -m "Message"

### Push Branch to Remote Repository
1. $git push -u origin branchname (the -u will associate the branchname so next time we pull and push we just call git pull and git pull)
2. $git branch -A

### Merge Branch
1. $ git checkout master (go to master branch)
2. $ git pull origin master
3. $ git branch --merged (check the branches that we've merged in so far)
4. $ git merge branchname
5. $ git push origin master

### Delete Branch
1. $ git branch (first make sure the branch is merged)
2. $ git branch -d branchname

### Delete Branch from the Remote Repository
1. $ git push origin --delete branchname