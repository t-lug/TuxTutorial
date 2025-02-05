# Git Cheat Sheet

## Basic Commands
- `git init`: Initialize a new Git repository.
- `git clone <repo-url>`: Clone a repository to your local machine.
- `git status`: Check the status of your working directory.
- `git add <file>`: Stage changes for commit.
- `git commit -m "message"`: Commit changes with a message.
- `git push origin <branch>`: Push changes to a remote branch.
- `git pull`: Fetch and merge changes from the remote repository.

## Branching and Merging
- `git branch`: List all branches.
- `git checkout -b <branch-name>`: Create and switch to a new branch.
- `git merge <branch-name>`: Merge a branch into the current branch.
- `git branch -d <branch-name>`: Delete a branch.

## Resolving Conflicts
- Open the conflicting file and resolve the conflicts manually.
- Stage the resolved file using `git add <file>`.
- Complete the merge with `git commit`.

## Advanced Commands
- `git log`: View commit history.
- `git diff`: See changes between commits or branches.
- `git reset <file>`: Unstage a file.
- `git stash`: Temporarily save changes without committing.
