### Explore more about GitHub

1. Initialize a new Git repository:
    ```sh
    git init
    ```

2. Add all files to the staging area:
    ```sh
    git add .
    ```

3. Commit the staged files with a message:
    ```sh
    git commit -m "Initial commit"
    ```

4. Create or rename a branch to `main` (or any other name), or check existing branches:
    ```sh
    git branch -M main
    # OR for creating a new branch
    git branch new-branch-name
    # OR for checking branches
    git branch
    ```

5. Add a remote repository URL:
    ```sh
    git remote add origin https://github.com/your-username/your-repo.git
    ```

6. Push changes to the `main` branch on the remote repository:
    ```sh
    git push -u origin main
    ```

### Branch

1. Create a new branch:
    ```sh
    git branch your-new-branch
    ```

2. Switch to the newly created branch:
    ```sh
    git checkout your-new-branch
    ```

3. Create and switch to a new branch in one command:
    ```sh
    git checkout -b new-branch-name
    ```

4. Delete a branch locally:
    ```sh
    git branch -d branch-to-delete
    ```

5. Push the new branch to the remote repository:
    ```sh
    git push origin new-branch-name
    ```

6. Commit all changes with a message:
    ```sh
    git commit -am "Updated files"
    ```

### Undoing and Reverting Commits

1. Reset to a specific commit (all changes after this commit will be lost):
    ```sh
    git reset 123abc --hard
    ```

2. Revert a specific commit (create a new commit that undoes the changes):
    ```sh
    git revert a463bc
    ```

3. View commit history:
    ```sh
    git log
    ```
