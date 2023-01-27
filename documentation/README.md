git log
- show log of recent commits

git status
- show current status in git repo - tracked/untracked changes

git revert COMMITSHA
- roll back to a previous commit s a change and commit that change as a new commit 
- keep git commit histrory

git reset COMMITSHA
- roll back to a previous commit and delete all history after that point

git push
- push commit changes to remote repo

git push -u origin main
- u flag links local repo branch with remtoe so you can pull from it with a simple 'git pull'
- 

git pull
- copy any changes from remote repo down into local repo

git add
- add chages to staging area ready to be commited

git commit
- create a commit (a save point) for all staged changes

git remote -v (verbose)
- list connected remote repos for the local repo

git remote add REMOTENAME URL 
eg git remote add origin https://github.com/somerepo

eg git remote add upstream https://github.com/someotherperson/somerepo

