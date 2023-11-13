# ﻿Demo Repository

## Git Commands

1. git init
2. git status
3. git add README.md
4. git commit -m "Initial Commit"
5. git branch -M main
6. git remote add origin https://<repo-url>
7. git push -u origin main

## Branching in Git

1. git checkout -b feature-1 # This will create a new branch
2. git checkout main # This will switch to an already existing branch
3. git checkout feature-1 # Again switching back to the feature-1 branch

## Merge the branches

1. git diff # Shows the difference
2. git merge main #

## Delete a branch named feature-1
1. git branch -d feature-1

## Undo a stage file back to unstaged state
1. git reset

## Undo a commit locally and point to previous commit
1. git reset HEAD~1

## Undo a commit locally and point to previous commit
1. git reset HEAD~2

## Restore to a previous commit based on Hash
1. git reset 64d9bd8f87704b3e5a88ba14e93ed21b6113b10a

## Hard reset to a previous commit
1. git reset --hard 64d9bd8f87704b3e5a88ba14e93ed21b6113b10a