## Git & GitHub

# Git
- **Version Control Tool**
- **Version Control System**

### Git Commands

1. **`git init`**  
   Initializes an empty git repository.

2. **`git status`**  
   Gives the current state of the git repository:
   - Branch
   - Commit
   - Tracked / Untracked files

3. **`git checkout -b <branch-name>`**  
   Creates and switches to a new branch.  
   *(To switch to an existing branch, use `git checkout <branch-name>` without `-b`.)*

4. **`git add <file_name>`**  
   Stages the untracked file.

5. **`git branch`**  
   Lists all the branches in the git repository.

6. **`git commit -m "<message>"`**  
   Commits the staged files with a message.

7. **`git restore <file_name>`**  
   Unstages or reverts changes in the working directory.

8. **`git restore --staged <file_name>`**  
   Unstages a file that was added using `git add`.

9. **`git log`**  
   Displays the commit history.
   
11. **`git revert <commit-hash>`**  
   Reverts a specific commit.
