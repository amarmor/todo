To Do
=====

Git Workflow
------------
1. git status
  + this will show whether there are any modified files
2. git branch
  + this will list all of the branches. current branch will be green.
2.5 git checkout -b [branch_name]
  + this will create a new branch. if you wanna switch between branches, you don't have to write "-b"
3. git add [name of modified uncommitted file]
  + this will add it to a yet-unnamed commit
3. git commit -m "[message]"
  + saves modifications into a commit and names the commit
4. git pull origin [branch_name]
5. git push origin [branch_name]
6. go to github and create a pull request
7. if the pull request is safe to merge, then you merge it
  + this will create a new commit that combines the branch into your master branch. This means there's a new commit on the server that you don't have locally (namely, the merged commit into the master branch)
8. git checkout master
9. git branch -d [name of branch just merged]
  + don't do line 9 if you think you'll have to make additional changes in the branch
10. git pull origin master
  + this pulls down the commit of the merge

