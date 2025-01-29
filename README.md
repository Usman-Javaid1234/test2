Testing git/github by adding repo in my local machine.
Use "git init" for initializing the repo on local machine. Adds ".git" file in the folder.

use "git add ."
"git commit -m (message)"
then "git remote add origin (HTTP repo link)".

"git remote -v" to show connected repos
"git push -u origin main/master/branchname" to keep pushing to that repo/branch without writing onto that repo without writing origin main/etc.

"git branch" to check which branch you are on.

"git checkout -b  (branch name)" to create new branch.

Some more changes in branch.

"git diff (branch name)" from master to compare the 2 codes and see what is added and what is removed.

"git push --set-upstream origin feature/adding-instructions" to push code to branch in github repo.


"--set-upstream" can be replaced with "-u"

You make changes by creating branch, and then initiate a pull request, which is accepted by the repo owner and then by accepting the pull request, the branch is merged with main/master. 

To get the changes in local machine we use "git pull origin main/master".
If upstream is set then we use "git pull".


To delete a branch use "git branch -d (branch name)"

Use "git commit -am (message)" to add and commit with message at the same time. Only works with modified files.

Use "git merge (branch name)"  to merge code from one branch to your current branch. Useful if main/master in github keeps getting changed from other members PRs or merges and you have to stay upto date in your current branch so that there are no merge conflicts in the future. Also try to resolve conflicts in code editor, much easier.

#Undoing changes

Resetted changes using command "git reset".
Can also use "git reset (file name)".
"git reset HEAD" HEAD points to last commit.
"git reset HEAD~1" the ~1 makes it so that HEAD points to 1 commit before last commit, so it resets the changes made in last commit.

"git log" to see a log of commits.

"git reset (hash of a commit)" to go to that specific commit.