# git add

## What does `git add` do?

It moves changes from the working directory to the staging area.

## Commands

```bash
git add file.txt
git add .
git add -A
```

**Explanation**

`git add file.txt → stage a single file`

`git add . → stage all files in current directory`

`git add -A → stage everything (new, modified, deleted)`

**Important**

`git add does NOT create a commit.`
`It only prepares changes for commit.`
