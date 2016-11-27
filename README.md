# README
==========

Github Practice
Learning how to use Git using command-line

1. git init
2. create txt file
3. git status
4. git add file.txt (to track)
5. git commit -m "Message for the commit"
6. git remote add origin "https://github.com/rchrdl/reponame.git
7. git push -u origin master


### Git Pulls and Branches
1. git pull
2. git branch "branchname" (use prefixes e.g. testbranch/branch-1)
3. git checkout testbranch/branch-1 (move to this branch, and only start making changes here)
4. git status
5. git add "filename"
6. git commit -m "Commit message"
7. git push origin testbranch/branch-1 (push changes to this remote branch)

### Pull Request
1. Raise a pull request for code review before merging

### Merge
1. git checkout master
2. git merge testbranch/branch-1
3. git commit
4. git push


### Notes
To open file
- vim "filename"

To save and close
- esc
- :x

To delete branch
- git branch -d branchname

