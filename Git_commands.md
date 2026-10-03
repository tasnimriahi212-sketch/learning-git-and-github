# Git Commands

Common Git commands with a brief description of what each one does.

## Start and configure

| Command | Description |
|---|---|
| `git init` | Create a new Git repository in the current folder. |
| `git clone <url>` | Copy a remote repository to your computer. |
| `git config --global user.name "Your Name"` | Set the author name used in your commits. |
| `git config --global user.email "you@example.com"` | Set the author email used in your commits. |

## Check and save changes

| Command | Description |
|---|---|
| `git status` | Show changed, staged, and untracked files. |
| `git diff` | View unstaged changes line by line. |
| `git diff --staged` | View changes staged for the next commit. |
| `git add <file>` | Stage a file for the next commit. |
| `git add .` | Stage all changes in the current folder. |
| `git commit -m "message"` | Save staged changes with a descriptive message. |
| `git log --oneline` | Show a compact list of recent commits. |

## Branches and merging

| Command | Description |
|---|---|
| `git branch` | List local branches. |
| `git switch <branch>` | Switch to an existing branch. |
| `git switch -c <branch>` | Create a branch and switch to it. |
| `git merge <branch>` | Merge the named branch into the current branch. |
| `git branch -d <branch>` | Delete a branch that has already been merged. |

## Remotes and syncing

| Command | Description |
|---|---|
| `git remote -v` | Show the repository's remote connections. |
| `git fetch` | Download remote updates without merging them. |
| `git pull` | Fetch remote updates and integrate them into the current branch. |
| `git push` | Send local commits to the remote repository. |
| `git push -u origin <branch>` | Push a new branch and set its upstream remote. |

## Undo and inspect

| Command | Description |
|---|---|
| `git show <commit>` | Display the changes and details of a commit. |
| `git restore <file>` | Discard unstaged changes to a file. |
| `git restore --staged <file>` | Unstage a file while keeping its changes. |
| `git revert <commit>` | Create a new commit that reverses an earlier commit. |
| `git stash` | Temporarily put aside uncommitted changes. |
| `git stash pop` | Reapply the most recently stashed changes. |

**Tip:** Check `git status` before staging, committing, or undoing changes. Be careful with commands such as `git reset --hard`, which can permanently discard work.
