# My Git cheatsheet

## Creating a Git Repo

In the folder you want to create a repo, do the following in terminal

```
git init

```

\*\*Always check that you are not already in a repo by using git status

---

## Adding files to staging

Staging is files that being tracked to be committed

use git status to see files which are untracked(red) or in staging(green)

```
git status
```

three ways to add files to staging

- add one file at a time `git add <filename>`
- add all files in the repo `git add -A`
- add all files in my current folder with `git add

---

## Committing Files to Our Repo

```
git commit -m "some random text, something descriptive"
```

**If you forget the -m, you'll end up in vim, to exit type ":wq"**

## Looking at our commit history

```
git log
```

```
git log --oneline
```
