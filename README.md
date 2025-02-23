# Github 101

## Configure Git
Set your username and email for Git commits:
```bash
git config --global user.name "Your Name"
```
```bash
git config --global user.email "your.email@example.com"
```
Get your username and email:
```bash
git config --global user.name
```
```bash
git config --global user.email
```

## Create a Basic HTML File
Create an `index.html` file with the following content:
```html
<!DOCTYPE html>
<html>
<head>
    <title>Hello World</title>
</head>
<body>
    <h1>Hello, World!</h1>
</body>
</html>
```

## Check Status
See the current state of your Git repository:
```bash
git status
```

## Initialize a Repository
Create a new Git repository:
```bash
git init
```

## Check Status Again
Verify the repository status after adding the new file:
```bash
git status
```

## Stage Files
Add files to the staging area:
```bash
git add index.html
```

## Commit Changes
Save changes in the local repository:
```bash
git commit -m "Initial commit"
```

## Understand Git Workflow
Git follows this workflow:
- Working Directory → Staging Area → Repository → Remote Repository

## View Commit History
Check the commit logs:
```bash
git log
```

## Add Remote Repository
Connect the local repository to a remote GitHub repository:
```bash
git remote add origin https://github.com/yourusername/repository.git
```

## Push to Remote Repository
Upload local commits to GitHub:
```bash
git push -u origin main
```

## Pull Changes from Remote
After making changes on GitHub, update the local repository:
```bash
git pull origin main
```

## Clone a Repository
Copy an existing GitHub repository to your local machine:
```bash
git clone https://github.com/yourusername/repository.git
```

## Check Status Again
After cloning, check the repository status:
```bash
git status
```

## Stage and Commit Changes
Add and commit changes before pushing:
```bash
git add .
git commit -m "Updated files"
```

## Push to Remote Repository
Send committed changes to GitHub:
```bash
git push origin main
```

## View Commit History Again
Check commit logs after pushing:
```bash
git log
```

## Undo Changes Before Commit
Unstage changes but keep them in the working directory:
```bash
git reset
```

## Undo Commit and Keep Changes Staged
Undo last commit while keeping changes in the staging area:
```bash
git reset --soft HEAD~1
```

## Undo Commit and Remove All Changes
Undo last commit and discard all changes:
```bash
git reset --hard HEAD~1
```

## Extra: Working with Branches
### Create a New Branch
```bash
git branch new-feature
```

### List All Branches
```bash
git branch
```

### Switch to the New Branch
```bash
git checkout new-feature
```

### Make Changes and Commit in the New Branch
Modify a file, then stage and commit:
```bash
git add .
git commit -m "Changes in new feature branch"
```

### Switch Back to Main Branch
```bash
git checkout main
```

### Merge Branch into Main
```bash
git merge new-feature
```

### Delete the Merged Branch
```bash
git branch -d new-feature
```

### Create and Switch to a New Branch in One Command
```bash
git checkout -b another-feature
```

This guide provides the essential Git commands for beginners using Git and GitHub with Bash.
