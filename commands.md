# Commands
## Basics
- `git clone <url>` - makes a local clone of your the repository specified in the url
- `git pull` - gets the latest version of a remote repository
- `git commit -m "<message>"` - saves your changes to a new github commit
- `git push` - pushes your commits to a remote repository
- `git add <file>` - stages the current state of a file, ready to be committed
- `git add .` - stages the current state of all files
## Branching
- `git branch <branch>` - creates a branch with a provided name
- `git checkout <branch>` - switch to an existing branch
- `git checkout -b <branch>` - create and switch to a branch
- `git stash` - save your changes locally, used before switching branches
- `git stash pop` - removes the stashed changes
- `git merge <branch>` - merges the specified branch into the current one
- `git push origin <branch>` - same as git push, but you have to do this command the first time you push a local branch to a remote repository (reason is confusing I can explain if you really want)
- `git branch -d <branch>` - deletes a branch
- `git branch` - lists all branches
## More help
- See the [Git Cheat Sheet](https://git-scm.com/cheat-sheet) from the [git docs](https://git-scm.com/doc)

Hello! this is a change