## List of the most popular commands for git and examples for them

### Git Commands and Their Expanded Usage

1. `git config`
   - Description: Configure Git settings.
   - Examples:
     - Set user name: `git config --global user.name "Your Name"`
     - Set email: `git config --global user.email "your_email@example.com"`
     - List all settings: `git config --list`
     - Set default branch name: `git config --global init.defaultBranch main`
     - Set color UI: `git config --global color.ui auto`

2. `git clone`
   - Description: Clone a repository.
   - Examples:
     - Clone a repository: `git clone https://github.com/user/repo.git`
     - Clone into a specific folder: `git clone https://github.com/user/repo.git folder-name`
     - Clone a specific branch: `git clone -b branch-name https://github.com/user/repo.git`
     - Clone with a specific depth: `git clone --depth 1 https://github.com/user/repo.git`

3. `git status`
   - Description: Show the working tree status.
   - Examples:
     - Check status: `git status`
     - Check in short format: `git status -s`
     - Show branch information: `git status -b`
     - Show ignored files: `git status --ignored`

4. `git log`
   - Description: Show commit logs.
   - Examples:
     - Show history: `git log`
     - Show history with diff: `git log -p`
     - Show specific number of commits: `git log -n 5`
     - Show log with graph: `git log --graph`
     - Show stats for each commit: `git log --stat`

5. `git diff`
   - Description: Show changes.
   - Examples:
     - Show changes: `git diff`
     - Show changes of a file: `git diff myfile.txt`
     - Show changes between commits: `git diff commit1..commit2`
     - Show staged changes: `git diff --staged`
     - Show summary of changes: `git diff --summary`

6. `git fetch`
   - Description: Download changes.
   - Examples:
     - Fetch changes: `git fetch origin`
     - Fetch all branches: `git fetch --all`
     - Fetch a specific branch: `git fetch origin branch-name`
     - Fetch and prune: `git fetch -p`

7. `git pull`
   - Description: Fetch and integrate changes.
   - Examples:
     - Pull changes: `git pull origin master`
     - Pull with rebase: `git pull --rebase origin master`
     - Pull all branches: `git pull --all`
     - Pull and show commit messages: `git pull --verbose`

8. `git merge`
   - Description: Merge development histories.
   - Examples:
     - Merge a branch: `git merge feature-branch`
     - Merge with commit message: `git merge feature-branch -m "Merging feature"`
     - Merge and squash commits: `git merge --squash feature-branch`
     - Abort a merge: `git merge --abort`

9. `git branch`
   - Description: Manage branches.
   - Examples:
     - Create a branch: `git branch new-branch`
     - Delete a branch: `git branch -d old-branch`
     - List all branches: `git branch -a`
     - Rename a branch: `git branch -m old-name new-name`
     - Show merged branches: `git branch --merged`

10. `git checkout`
    - Description: Switch branches or restore files.
    - Examples:
      - Switch to a branch: `git checkout branch-name`
      - Create and switch to new branch: `git checkout -b new-branch`
      - Restore a file: `git checkout -- file.txt`
      - Checkout a remote branch: `git checkout -b branch-name origin/branch-name`
      - Checkout a specific commit: `git checkout commit-hash`

11. `git commit`
    - Description: Record changes.
    - Examples:
      - Commit with a message: `git commit -m "Commit message"`
      - Amend the last commit: `git commit --amend`
      - Commit specific files: `git commit file1.txt file2.txt -m "Commit message"`
      - Commit with all changes: `git commit -a -m "Commit message"`
      - Commit with a sign-off: `git commit -s -m "Commit message"`

12. `git remote`
    - Description: Manage remote repositories.
    - Examples:
      - List remotes: `git remote -v`
      - Add a remote: `git remote add origin https://github.com/user/repo.git`
      - Remove a remote: `git remote remove origin`
      - Rename a remote: `git remote rename origin new-origin`
      - Set URL of a remote: `git remote set-url origin https://github.com/new-user/repo.git`

13. `git push`
    - Description: Update remote refs.
    - Examples:
      - Push changes: `git push origin master`
      - Push a new branch: `git push origin new-branch`
      - Delete a remote branch: `git push origin --delete old-branch`
      - Push all branches: `git push --all origin`
      - Push tags: `git push --tags`

14. `git reset`
    - Description: Reset current HEAD.
    - Examples:
      - Soft reset: `git reset --soft HEAD~1`
      - Hard reset: `git reset --hard HEAD~1`
      - Reset a specific file: `git reset file.txt`
      - Reset to a specific commit: `git reset --hard commit-hash`
      - Reset and preserve uncommitted local changes: `git reset --keep commit-hash`

15. `git rebase`
    - Description: Reapply commits.
    - Examples:
      - Rebase a branch: `git rebase master`
      - Interactive rebase: `git rebase -i HEAD~3`
      - Abort a rebase: `git rebase --abort`
      - Continue after resolving conflicts: `git rebase --continue`
      - Skip a commit during rebase: `git rebase --skip`
