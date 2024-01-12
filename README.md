##  EXPLAIN VERSION CONTROL
*Version control is a system that records changes to a file or set of files over time so that you can recall specific versions later.*

## DIFFERENCE BETWEEN GIT AND GITHUB
### GIT
*Git is a version control system that lets you manage and keep track of your source code history*
### GITHUB
** GitHub is a cloud-based hosting service that lets you manage Git repositories.**

### LIST 3 OTHER GITHUB
1. Gitlab
2. Bitbucket
3. SourceForge
   
## EXPALAIN THE DIFFERENCE BETWEEN GIT FETCH AND GIT PULL
**Git fetch basically imports the commits to local branches so as to keep up-to-date that what everybody is working on**
**Git Pull basically brings the local branch up-to-date with the remote copy that will also updates the other remote tracking branches.**

## EXPLAIN IN SIMPLE TERMS GIT REBASE AND THE COMMAND FOR IT
*Git rebase is changing the base of your branch from one commit to another making it appear as if you'd created your branch from a different commit.*
### The command
1. Go to the branch in need of rebasing
2. Enter git fetch origin (This syncs your main branch with the latest changes)
3. Enter git rebase origin/main
4. Fix merge conflicts that arise however you see fit.
5. After fixing merge conflicts, git add FILE previously merge conflicted files
6. Enter git rebase --continue
7. Repeat as necessary as merge conflicts arise in the subsequent commits
8. Once the rebase is complete, enter git push origin HEAD --force
   
## EXPLAIN IN SIMPLE TERMS GIT CHERRY-PICK AND THE COMMAND FOR IT
*git cherry-pick in git means choosing a commit from one branch and applying it to another branch. 
This is in contrast with other ways such as merge and rebases which normally apply many commits into another branch.*
### The command
**git cherry-pick is a powerful command that enables arbitrary Git commits to be picked by reference and appended to the current working HEAD**