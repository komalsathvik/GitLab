# git reset

## Description

Used to undo commits or move changes out of staging.

## Soft Reset

```bash
git reset --soft HEAD~1
```

````

**Mixed Reset (default)**

```
git reset HEAD~1

Removes commit
Keeps changes unstaged
```

**Hard Reset ⚠️**

```
git reset --hard HEAD~1

Removes commit

Deletes changes permanently
```

**Warning**

Avoid --hard unless you are absolutely sure.
````
