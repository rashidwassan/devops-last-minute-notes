# Comprehensive Git Guide

Git is a distributed version control system that lets you manage and keep track of your source code history. This guide provides a comprehensive overview of Git commands, grouped by functionality.

## Basic Git Commands

### 1. **`git init`**
   - **Usage:** Initializes a new Git repository.
   - **Example:** `git init`

### 2. **`git clone [url]`**
   - **Usage:** Clones a repository into a new directory.
   - **Example:** `git clone https://github.com/username/repository.git`

### 3. **`git add [file]`**
   - **Usage:** Adds files to the staging area for Git.
   - **Example:** `git add index.html` (Adds a single file)
   - **Example:** `git add .` (Adds all changed files)

### 4. **`git commit -m "[commit message]"`**
   - **Usage:** Records file snapshots permanently in version history.
   - **Example:** `git commit -m "Add initial project version"`

### 5. **`git status`**
   - **Usage:** Displays the state of the working directory and staging area.
   - **Example:** `git status`

### 6. **`git push [alias] [branch]`**
   - **Usage:** Uploads all local branch commits to GitHub.
   - **Example:** `git push origin master`

### 7. **`git pull`**
   - **Usage:** Fetches and integrates changes from the remote server to your working directory.
   - **Example:** `git pull origin master`

### 8. **`git branch`**
   - **Usage:** Lists, creates, or deletes branches.
   - **Example:** `git branch` (Lists all branches)
   - **Example:** `git branch new-branch` (Creates a new branch)

### 9. **`git checkout [branch-name]`**
   - **Usage:** Switches branches or restores working tree files.
   - **Example:** `git checkout master` (Switches to the 'master' branch)
   - **Example:** `git checkout -b new-branch` (Creates and switches to a new branch)

### 10. **`git merge [branch]`**
  - **Usage:** Merges a specified branch into the current branch.
  - **Example:** `git merge feature-branch`

### 11. **`git diff`**
  - **Usage:** Shows file differences not yet staged.
  - **Example:** `git diff`

### 12. **`git reset [file]`**
   - **Usage:** Unstages specified files from the current commit.
   - **Example:** `git reset HEAD index.html` (Unstages 'index.html')

### 13. **`git log`**
   - **Usage:** Displays commit logs.
   - **Example:** `git log`

## Advanced Git Commands

### 14. **`git stash`**
  - **Usage:** Temporarily stores all modified tracked files.
  - **Example:** `git stash`

### 15. **`git stash pop`**
   - **Usage:** Restores the most recently stashed files.
  - **Example:** `git stash pop`

### 16. **`git rebase [branch]`**
  - **Usage:** Reapplies commits on top of another base tip.
  - **Example:** `git rebase master`

### 17. **`git tag [tag-name]`**
   - **Usage:** Marks a significant change set, such as a release.
   - **Example:** `git tag v1.0.0`

### 18. **`git fetch [alias]`**
  - **Usage:** Downloads all changes from the remote, but doesn't integrate into HEAD.
  - **Example:** `git fetch origin`

### 19. **`git remote -v`**
   - **Usage:** Lists all currently configured remote repositories.
   - **Example:** `git remote -v`

### 20. **`git remote add [alias] [url]`**
  - **Usage:** Adds a new remote Git repository as a shortcut.
  - **Example:** `git remote add origin https://github.com/username/repository.git`

## Configuration Commands

### 21. **`git config --global user.name "[name]"`**
  - **Usage:** Sets the name you want attached to your commit transactions.
  - **Example:** `git config --global user.name "John Doe"`

### 22. **`git config --global user.email "[email address]"`**
  - **Usage:** Sets the email you want attached to your commit transactions.
    - **Example:** `git config --global user.email johndoe@example.com`

### 23. **`git rebase -i [base]`**
  - **Usage:** Rebase interactively, which allows you to modify commits in the process of rebasing.
    - **Example:** `git rebase -i HEAD~3` (Interactively rebase the last three commits)

### 24. **`git cherry-pick [commit]`**
  - **Usage:** Apply the changes introduced by some existing commits.
    - **Example:** `git cherry-pick 4a2a5b3`

### 25. **`git rm [file]`**
   - **Usage:** Removes files from the working tree and from the index.
    - **Example:** `git rm file.txt`

### 26. **`git revert [commit]`**
  - **Usage:** Creates a new commit that undoes all of the changes made in a specified commit, then applies it to the current branch.
    - **Example:** `git revert 0ad5a7a6`

### 27. **`git bisect start`**
  - **Usage:** Use binary search to find the commit that introduced a bug.
    - **Example:** `git bisect start`

### 28. **`git bisect bad`**
   - **Usage:** Marks the current revision as bad (buggy).
    - **Example:** `git bisect bad`

### 29. **`git bisect good [commit]`**
  - **Usage:** Marks the commit as good, where the bug is not present.
    - **Example:** `git bisect good 4a2a5b3`

### 30. **`git bisect reset`**
   - **Usage:** Ends the bisect session and returns to the previous branch.
    - **Example:** `git bisect reset`

### 31. **`git blame [file]`**
- **Usage:** Shows what revision and author last modified each line of a file.
    - **Example:** `git blame README.md`

### 32. **`git stash list`**
  - **Usage:** Lists all stashed changesets.
    - **Example:** `git stash list`

### 33. **`git stash apply`**
  - **Usage:** Applies a stashed workspace onto the current working directory.
    - **Example:** `git stash apply`

### 34. **`git stash drop [stash_id]`**
  - **Usage:** Removes a single stashed state from the stash list.
    - **Example:** `git stash drop stash@{0}`

### 35. **`git stash clear`**
  - **Usage:** Removes all the stashed states.
    - **Example:** `git stash clear`

### 36. **`git clean -n`**
  - **Usage:** Shows which files would be removed from working directory.
    - **Example:** `git clean -n`

### 37. **`git clean -f`**
  - **Usage:** Forcefully removes files from the working directory.
    - **Example:** `git clean -f`

### 38. **`git log --oneline`**
  - **Usage:** Condenses each commit to a single line.
    - **Example:** `git log --oneline`

### 39. **`git log --graph`**
  - **Usage:** Displays the commit tree graphically.
    - **Example:** `git log --graph`

### 40. **`git log --stat`**
   - **Usage:** Shows stats (file modifications, additions, deletions) about commits.
    - **Example:** `git log --stat`

### 41. **`git log -p [file]`**
  - **Usage:** Shows commit logs and generates patches of each commit.
    - **Example:** `git log -p README.md`

### 42. **`git show [commit]`**
  - **Usage:** Shows various types of objects (commits, tags, etc.).
    - **Example:** `git show 1a2b3c4`

### 43. **`git reflog`**
  - **Usage:** Reference logs, or "reflogs", are a mechanism to record when the tips of branches and other references were updated in the local repository.
    - **Example:** `git reflog`

### 44. **`git fetch --prune`**
   - **Usage:** Fetches and removes any remote-tracking references that no longer exist on the remote.
    - **Example
### 45. **`git fetch --all`**
   - **Usage:** Fetches all changes from all remotes.
    - **Example:** `git fetch --all`

### 46. **`git push --force`**
   - **Usage:** Forces the git push even if it results in a non-fast-forward merge. Use with caution as it can overwrite changes.
    - **Example:** `git push --force`

### 47. **`git push --tags`**
   - **Usage:** Pushes tags to remote repository.
    - **Example:** `git push --tags`

### 48. **`git tag -a [tag-name] -m [message]`**
   - **Usage:** Creates an annotated tag, which is stored as a full object in the Git database.
    - **Example:** `git tag -a v1.0 -m "Initial release version"`

### 49. **`git show-ref`**
  - **Usage:** Lists references in a local repository, such as heads, tags, and remotes.
    - **Example:** `git show-ref`

### 50. **`git branch -d [branch-name]`**
   - **Usage:** Deletes a branch locally. Use `-D` to force delete a branch that hasn't been merged.
    - **Example:** `git branch -d feature-branch`

### 51. **`git branch -m [old-branch-name] [new-branch-name]`**
  - **Usage:** Renames a branch.
    - **Example:** `git branch -m old-branch new-branch`

### 52. **`git branch -r`**
   - **Usage:** Lists remote-tracking branches.
    - **Example:** `git branch -r`

### 53. **`git remote rename [old-name] [new-name]`**
   - **Usage:** Renames a remote.
    - **Example:** `git remote rename origin upstream`

### 54. **`git remote remove [remote-name]`**
  - **Usage:** Removes a remote.
    - **Example:** `git remote remove upstream`

### 55. **`git remote set-url [remote-name] [new-url]`**
   - **Usage:** Changes the URL for a remote.
    - **Example:** `git remote set-url origin https://newurl.com/repo.git`

### 56. **`git archive --format=tar --output=/path/to/output.tar [branch]`**
   - **Usage:** Creates an archive of the specified format containing the tree structure for a source tree.
    - **Example:** `git archive --format=tar --output=./output.tar master`

### 57. **`git gc`**
  - **Usage:** Cleans up unnecessary files and optimizes the local repository.
    - **Example:** `git gc`

### 58. **`git fsck`**
   - **Usage:** Verifies the integrity of the Git file system, checking for corrupt objects.
    - **Example:** `git fsck`

### 59. **`git prune`**
  - **Usage:** Prunes all unreachable objects from the object database.
    - **Example:** `git prune`

### 60. **`git ls-files`**
  - **Usage:** Shows information about files in the index and the working tree.
    - **Example:** `git ls-files`

This comprehensive list of Git commands should provide a strong foundation for managing your projects using version control with Git. Each command has been designed to offer specific functionalities needed for effective version management.


