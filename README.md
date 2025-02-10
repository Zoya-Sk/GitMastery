# Git & GitHub Learning Progress

## About This Repository
This is my Local Repository, which I use to track my Git and GitHub learning progress. I have been learning various Git commands and workflows while working with this repo.

## Commands I've Learned So Far

### Remote Repository Handling
- `git remote add origin <repo_url>` → Connects the local repository to a remote GitHub repository.
- `git remote -v` → Checks which remote repository the local repo is connected to.

### Branch Management
- `git branch` → Lists all branches in the repository.
- `git branch <branch_name>` → Creates a new branch.
- `git checkout <branch_name>` → Switches to the specified branch.
- `git merge <branch_name>` → Merges the specified branch into the current branch.

### Workflow Commands
- `git clone <repo_url>` → Clones a repository from GitHub to the local machine.
- `git status` → Checks the current status of the repository (modified, staged, or untracked files).
- `git add <file>` → Stages a specific file for commit.
- `git add .` → Stages all modified and new files for commit.
- `git commit -m "message"` → Commits the staged changes with a descriptive message.
- `git push origin <branch_name>` → Pushes the committed changes to GitHub.
- `git pull origin <branch_name>` → Pulls the latest changes from GitHub.

### Undo & Reset
- `git reset --soft HEAD~1` → Removes the last commit but keeps changes staged.
- `git reset --hard HEAD~1` → Removes the last commit and discards changes.
- `git checkout -- <file>` → Reverts changes in a specific file to the last committed state.

## My Git Workflow
1. Create a repository on GitHub.
2. Clone it to my local system using `git clone`.
3. Make changes in files.
4. Stage the changes using `git add`.
5. Commit the changes using `git commit`.
6. Push the changes to GitHub using `git push`.
7. If needed, pull updates using `git pull`.

---

## Will be adding further commands and updates in future.