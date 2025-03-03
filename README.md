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

If you want to add all untracked files to the staging area at once:
```bash
git add .
```

## Commit Changes
Save changes in the local repository:
```bash
git commit -m "Initial commit"
```

## Understand Git Workflow
Git follows this workflow:
- Working Directory → Staging Area → Repository → Remote Repository


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

## View Commit History Again
Check commit logs after pushing:
```bash
git log
```

This guide provides the essential Git commands for beginners using Git and GitHub with Bash.
