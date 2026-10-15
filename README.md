# Git Operations Using GitHub and Visual Studio Code

## Aim
To perform Git operations using GitHub and Visual Studio Code to manage files between a local working directory and a remote GitHub repository.

## Objectives
- Create and configure a GitHub repository.
- Clone a remote repository into a local working directory.
- Create, modify, and delete files.
- Track changes using Git.
- Stage and commit files.
- Push and pull changes between local and remote repositories.
- Create and manage branches.
- Merge branches and create pull requests.
- Verify repository synchronization.

## Tools Required
- Git
- GitHub account
- Visual Studio Code
- Web browser

## Git Commands

```bash
git --version
git config --global user.name "Your Name"
git config --global user.email "your-email@example.com"
git clone <repository-URL>
git status
git add .
git commit -m "Initial commit"
git push origin main
git pull origin main
git init
git remote add origin <repository-URL>
git branch
git branch -a
git checkout -b feature1
git fetch origin
git diff main..feature1
git merge feature1
git log --oneline
```

## Procedure
1. Create a GitHub account and a new repository.
2. Install Git and Visual Studio Code.
3. Configure the Git username and email address.
4. Clone the GitHub repository into the local working directory.
5. Create, modify, and delete files in VS Code.
6. Check file status, stage changes, and commit them.
7. Push local commits to GitHub and pull remote changes.
8. Initialize a new local repository using `git init`.
9. Connect the local repository to GitHub and push the files.
10. Create branches and perform file operations in the branches.
11. Compare and merge branches.
12. Create and merge a pull request through GitHub.
13. Verify synchronization between the local and remote repositories.

## Result
Git operations were performed using GitHub and Visual Studio Code. File management, staging, committing, pushing, pulling, branch operations, merging, pull requests, and repository synchronization were demonstrated successfully.
