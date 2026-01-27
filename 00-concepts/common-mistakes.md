# Common Beginner Mistakes

### 1. Pushing node_modules
Beginners sometimes push `node_modules` to GitHub.  
It’s very large and shouldn’t be tracked.

**Fix:** Add it to `.gitignore`:
```bash
node_modules/
```

If already pushed:
```bash
git rm -r --cached node_modules
git commit -m "Remove node_modules from repos."
```

### 2. Forgetting Current Branch
Working on the wrong branch can cause problems.

**Fix:** Check branch:
```bash
git branch
git checkout -b feature-branch
```

### 3. Not Committing Changes

Sometimes beginners forget to commit their changes.

Fix:
```bash
git status
git add .
git commit -m "Add feature"
```

### 4. Not Pulling Before Pushing

Pushing without pulling may cause conflicts.

Fix:
```bash
git pull origin main
git push
```

### 5. Editing Code Directly on GitHub

Editing in browser can cause confusion.

Fix:
Make changes locally, commit, and push.

### 6. Forgetting .gitignore

Unwanted files get tracked.

Fix:
Create .gitignore and list unwanted files.

```bash
node_modules/
.env
dist/
```