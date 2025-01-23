`git status`

### Possible Outputs:

#### 1. If the file is tracked and has changes, you’ll see something like:

```
Changes not staged for commit:
  (use "git add <file>" to update what will be committed)
  (use "git restore <file>" to discard changes in working directory)

    modified:   filename.html
```

#### 2. If the file is new (untracked), you’ll see:

```
Untracked files:
  (use "git add <file>" to include in what will be committed)

    filename.html
```

#### 3. If the file is already committed and up to date, Git will say:

```
nothing to commit, working tree clean
```

#### 4. If the directory is not a Git repository, you’ll see:

```
fatal: not a git repository (or any of the parent directories): .git
```

#### If you get the last error, initialize a Git repository by running:

```
git init
```

Let me know if you need further help! 🚀
