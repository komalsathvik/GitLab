# Essential Git & GitHub Best Practices

### 1. Check Status Often
```bash
git status
```
### 2. Commit Frequently
Make small, meaningful commits.

### 3. Write Clear Commit Messages
```bash
git commit -m "Add login page UI"
``` 

### 4. Pull Before Push
```bash
git pull origin main
```

### 5. Never Push node_modules
Add to .gitignore:
```bash
node_modules/
.env
```

### 6. Use Branches for Features
```bash
git checkout -b feature-name
```

### 7. Push Regularly
    Don't keep changes only locally.

### 8. Add README.md
    Explain project purpose and setup.

### 9. Review Changes Before Commit
```bash
git diff
```

### 10. Keep main Branch Clean
    Only stable code goes to main.