# Simple Git Workflow

This guide shows a beginner-friendly Git workflow for pushing projects to GitHub.

---

### 1. New Project - GitHub Workflow

Whenever you are starting the project:
```bash
git init #1. Initialize Git
git status  #2. Check Status
git add . #3. Add files to staging
git commit -m "Initial commit" #4. Commit changes

#5. Create repository on GitHub
(Create an empty repository — no README, no .gitignore)

git remote add origin https://github.com/username/repo-name.git (your repo-name url) #6. Connect local project to GitHub
#7. Push to GitHub
git branch -M main 
git push -u origin main 
``` 

### 2. Daily Workflow

Whenever you change code:
```bash
git status
git add .
git commit -m "Describe your change"
git push
```

### 3. Feature - branch workflow

Whenever you want to contribute to other's repo:
```bash
git clone <repo-url> # 1. Clone the Repository
cd project-folder

git checkout -b feature-branch (branch-name) # 2. Create a New Branch

### 3. Make Changes
Edit files in your code editor.

git status # 4. Check Status

git add . # 5. Stage Changes

git commit -m "Add new feature" (commit message) # 6. Commit Changes

git pull origin main # 7. Pull Latest Changes

git push origin feature-branch (branch-name) # 8. Push Your Branch

# 9. Open Pull Request
Go to GitHub and open a Pull Request.

# 10. Review and Merge
After review, changes get merged. 
```