### Git Commands Cheat Sheet

1. Initialize a Git repository:
```
git init
```

2. Check the repository status:
```
git status
```

3. Add changes to the staging area:
```
git add . or git add fileName
```

4. Commit changes with a message:
```
git commit -m "message"
```

5. View the commit history:
```
git log
```

6. Compare changes between the working directory and the staging area:
```
git diff
```

7. Compare changes between the staging area and the previous commit:
```
git diff --staged
```


8. Directly commit changes to tracked files (skip staging):
```
git commit -a -m "Direct Commit"
```

9. Remove a file and stage the deletion:
```
git rm filename
```

10. Rename a file and stage the rename operation:
 ```
 git mv oldname newname
 ```

11. Stop tracking a file but keep it in the working directory:
 ```
 git rm --cached filename
 ```

12. View the commit log in a one-line format:
 ```
 git log --pretty=oneline
 ```

13. Unstage changes for a specific file:
 ```
 git restore --staged filename
 ```

14. Discard changes in the working directory for a specific file:
 ```
 git checkout -- filename
 ```

15. Forcefully checkout the previous commit (discard local changes):
 ```
 git checkout -f
 ```

16. Create a global Git alias (e.g., `git st` for `git status`):
 ```
 git config --global alias.st status
 ```

17. Create a new branch and switch to it:
 ```
 git checkout -b branchname
 ```

18. Switch to an existing branch:
 ```
 git checkout branchname
 ```

19. List all branches in the repository:
 ```
 git branch
 ```

20. List branches that have been merged into the current branch:
 ```
 git branch --merged
 ```

21. Delete a branch if it has been merged into the current branch:
 ```
 git branch -d branchname
 ```

22. Forcefully delete a branch (without checking for merges):
 ```
 git branch -D branchname
 ```

23. List branches that haven't been merged into the current branch:
 ```
 git branch --no-merged
 ```

27. Delete remote branch
```
git push -d origin branchname
```

Remember to adapt these commands to your specific Git workflow and repository needs. Always use caution when performing operations that involve branch deletion or discarding changes.
