# Git & GitHub Basics with Bash

## Checking Status
Use the following command to check the status of your repository:
```bash
git status
```

## Initializing a Repository
To start tracking a project with Git, initialize a new repository:
```bash
git init
```

## Checking Status Again
After initializing, check the status again to see the current state:
```bash
git status
```

## Adding Files to Staging Area
To stage changes for commit:
```bash
git add <file>
```
To add all changes:
```bash
git add .
```

## Committing Changes
To save the staged changes:
```bash
git commit -m "Commit message"
```

## Understanding Git Workflow
Git follows a simple workflow:
- Working Directory (where files are modified)
- Staging Area (where changes are added before commit)
- Local Repository (where committed changes are stored)
- Remote Repository (where changes are pushed to GitHub)

## Viewing Commit History
To see the commit history:
```bash
git log
```

## Adding Remote Repository
To link your local repository to a remote repository:
```bash
git remote add origin <repository-url>
```

## Pushing Changes to Remote Repository
To upload your commits to GitHub:
```bash
git push origin main
```

## Pulling Latest Changes from Remote
If changes were made on GitHub, pull them into your local repository:
```bash
git pull origin main
```

## Cloning a Repository
To create a local copy of an existing repository:
```bash
git clone <repository-url>
```

## Status, Add, Commit, and Push to Remote
After making changes, follow these steps:
```bash
git status
git add .
git commit -m "Updated files"
git push origin main
```

## Viewing Commit History Again
To check the commit history:
```bash
git log
```

## Undoing Changes
To unstage files before committing:
```bash
git reset <file>
```

## Undoing Last Commit but Keeping Changes Staged
```bash
git reset --soft HEAD~1
```

## Undoing Last Commit and Removing Changes
```bash
git reset --hard HEAD~1
```

---

# Extra: Working with Branches

## Creating a New Branch
```bash
git branch <branch-name>
```

## Listing All Branches
```bash
git branch
```

## Switching to a New Branch
```bash
git checkout <branch-name>
```

## Changing Files in a New Branch and Committing
After switching to the new branch, make changes and commit them:
```bash
git add .
git commit -m "Changes in new branch"
```

## Switching Back to Main Branch
```bash
git checkout main
```

## Merging a Branch into Main
```bash
git merge <branch-name>
```

## Deleting a Branch
```bash
git branch -d <branch-name>
```

## Creating and Switching to a New Branch in One Step
```bash
git checkout -b <branch-name>
