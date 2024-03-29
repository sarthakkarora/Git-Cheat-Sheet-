# Git Cheat Sheet

Git is a distributed version control system that helps developers collaborate on projects of any scale.


This is a Git cheat sheet providing various commands and explanations for common Git operations. It covers essential commands such as configuring user information, initializing a repository, adding and committing changes, checking status, viewing commit history, creating and switching branches, merging branches, adding and working with remote repositories, pushing and pulling changes, and dealing with conflicts.

Here's a brief summary of some key commands:

1. **Configuring user information:**
   - `git config --global user.name "Your Name"`
   - `git config --global user.email "your.email@example.com"`

2. **Initializing a repository:**
   - `git init`

3. **Adding and committing changes:**
   - `git add filename_here`
   - `git commit -m "Commit message"`

4. **Checking status and viewing commit history:**
   - `git status`
   - `git log`

5. **Creating, switching, and deleting branches:**
   - `git branch branch_name`
   - `git checkout branch_name`
   - `git branch -d branch_name`

6. **Merging branches:**
   - `git merge branch_name`

7. **Adding and working with remote repositories:**
   - `git remote add origin <remote_repo_url>`
   - `git remote show origin`
   - `git push`
   - `git pull`

8. **Pushing a new branch and forcing a push:**
   - `git push -u origin branch_name`
   - `git push -f`

9. **Checking Differences:**
   - `git diff`: Shows changes between commits, commit and working tree, etc.
   - `git diff --staged`: Shows changes staged for the next commit.

10. **Undoing Changes:**
    - `git checkout -- <file>`: Discards changes in the working directory.
    - `git reset HEAD <file>`: Unstages changes in the staging area.

11. **Stashing Changes:**
    - `git stash`: Stashes changes in the working directory.
    - `git stash pop`: Applies stashed changes to the working directory.

12. **Tagging Releases:**
    - `git tag <tag_name>`: Creates a lightweight tag.
    - `git tag -a <tag_name> -m "Message"`: Creates an annotated tag with a message.

13. **Viewing Diffs of Tags:**
    - `git difftool -d <tag1> <tag2>`: Views the changes between two tags using a difftool.

14. **Amending Commits:**
    - `git commit --amend`: Amends the last commit with staged changes.
    
15. **Resetting Commits:**
    - `git reset --soft HEAD~1`: Moves HEAD to the previous commit, keeping changes staged.
    - `git reset HEAD~1`: Moves HEAD to the previous commit, unstaging changes.
    - `git reset --hard HEAD~1`: Moves HEAD to the previous commit, discarding changes.

16. **Viewing Remote Branches:**
    - `git branch -r`: Lists remote branches.
    - `git remote -v`: Lists remote repositories and their URLs.

17. **Fetching and Pulling:**
    - `git fetch`: Downloads changes from a remote repository.
    - `git pull origin <branch_name>`: Fetches changes and merges them into the current branch.

18. **Creating Aliases:**
    - `git config --global alias.<alias_name> <git_command>`: Creates a shortcut alias for a Git command.

19. **Ignoring Files:**
    - Create a `.gitignore` file and add files or patterns to be ignored by Git.

20. **Inspecting a Repository:**
    - `git show <commit_id>`: Shows information about a specific commit.
    - `git fsck`: Verifies the integrity of the Git file system.
