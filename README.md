## Git Branching Practice

### Basic 'git' commands
* 'git init' - create new local repo
* 'git add .' - add current working directory to git index
* 'git commit -m "message"' - commit changes to local repo
* 'git status' - display status of local repo

### Basic Branching
* 'git branch branchName' - create local branch named 'branchName'
* 'git checkout branchName' - move to branch 'branchName'
* 'git branch' - display local branches and which we are on
* 'git checkout -b newBranch' - create and check out branch 'newBranch'

### Merging
* Add and commit local branch.
* Push local branch to remote.
* Pull 'master' from remote into local branches
```bash
git checkout newBranch
git pull origin master
```
* Resolve merge conflicts
* Commit and push local branch
```bash
git add .
git commit -m "Merging master with newBranch"
git push origin newBranch
```
* On GitHub, create Pull Request
* Teammates merge Pull Request into master.
