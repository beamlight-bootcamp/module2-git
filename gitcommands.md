**git status:**
The `git status` command is used to check the status of your working directory and staging area. It provides information about which files are modified, untracked, or staged for commit. This command is helpful to understand the current state of your repository.

Example:
```bash
git status
```

**git add:**
The `git add` command is used to add changes from your working directory to the staging area. It prepares the changes for the next commit. You can add specific files or include all changes with a wildcard.

Example:
```bash
git add filename.txt
```

**git commit:**
The `git commit` command is used to save the changes in the staging area to the local repository. It requires a commit message that describes the changes made in the commit.

Example:
```bash
git commit -m "Add new feature"
```

**git remote:**
The `git remote` command shows the remote repositories linked to your local repository. It allows you to manage connections to remote repositories.

Example:
```bash
git remote -v
```

**git push:**
The `git push` command is used to upload local repository changes to a remote repository. It updates the remote repository with the committed changes.

Example:
```bash
git push origin master
```

**git merge:**
The `git merge` command combines changes from different branches into the current branch. It is often used to integrate feature branches into the main branch.

Example:
```bash
git merge feature-branch
```

**git pull:**
The `git pull` command fetches changes from a remote repository and merges them into the current branch. It is a combination of `git fetch` and `git merge`.

Example:
```bash
git pull origin master
```

**git clone:**
The `git clone` command is used to create a copy of a remote repository on your local machine. It allows you to start working on a project without creating it from scratch.

Example:
```bash
git clone https://github.com/example/repository.git
```

**git branch:**
The `git branch` command shows a list of branches in your repository. It can also be used to create, delete, or rename branches.

Example:
```bash
git branch
```

**git checkout:**
The `git checkout` command is used to switch between branches or restore files from a specific commit. It helps navigate through different states of the repository.

Example:
```bash
git checkout feature-branch
```

**git reset:**
The `git reset` command is used to undo changes in your working directory or staging area. It allows you to unstage changes or reset to a specific commit.

Example:
```bash
git reset --hard HEAD
```
**git revert:**
The `git revert` command is used to create a new commit that undoes the changes made in a previous commit. It is a safe way to reverse commits without altering the commit history.

Example:
```bash
git revert <commit-hash>
```

**git commit --amend:**
The `git commit --amend` command is used to modify the last commit. It allows you to add changes to the previous commit or modify its commit message.

Example:
```bash
git commit --amend
```

**git stash:**
The `git stash` command is used to temporarily save changes that are not ready to be committed. It allows you to switch to another branch or perform other operations without committing incomplete work.

Example:
```bash
git stash
```

**git rebase:**
The `git rebase` command is used to change the commit history by moving, combining, or deleting commits. It helps create a cleaner and linear history.

Example:
```bash
git rebase master
```
**squash:**
Squashing commits is a process often performed during a git rebase to combine multiple commits into a single commit. It helps maintain a cleaner and more organized commit history.

Example (during rebase):
```bash
pick <commit-hash>
squash <commit-hash>
```

Please note that squashing involves combining commits, and the exact command may vary based on the specific commits you want to squash.

These commands provide essential functionality in Git, allowing developers to manage and control the version history of their projects efficiently.

**git init:**
The `git init` command is used to initialize a new Git repository. When executed in a directory, it transforms that directory into a Git repository, creating the necessary data structures and configuration files to start version control.

Example:
```bash
git init
```

After running this command, the directory will contain a hidden subfolder named `.git`, which stores the version history and configuration files. The repository is now ready to track changes, and you can proceed to add files, make commits, and manage the project's version history using other Git commands.

This command is typically used when starting a new project or when converting an existing project into a Git repository to begin tracking changes.