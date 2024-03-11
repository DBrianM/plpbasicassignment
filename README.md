Task 1: GitHub Repository Creation

1. Log in to your GitHub account
2. Create a new repository:
   - Click on the "+" sign in the top right corner.
   - Select "New repository."
   - Naming of the repository
   - Click "Create repository."
Task 2: Local Folder Setup
3. Create a new folder on  local machine:
   - Open your file explorer.
   - Create a new folder (e.g., "PLPBasicGitAssignment").
4. Open a terminal or command prompt:
   - Navigate to the created folder using the `cd` command.
     ```bash
     cd path/to/PLPBasicGitAssignment
     ```
Task 3: Git Initialization
5. Initialize a new Git repository:
   - Run the following command in your terminal.
     ```bash
     git init
     ```

6. Connecting to GitHub:
   - Link your local repository to the GitHub repository.
     ```bash
     git remote add origin <repository-url>
     ```
     Replace `<repository-url>` with the actual URL of your GitHub repository.

Task 4: Making Changes

7. Create a File:
   - Inside your local folder, create a new text file (e.g., `hello.txt`).
   - Add a simple text message (e.g., "Hello, Git!").

8. Committing Changes:
   - Stage the changes.
     ```bash
     git add hello.txt
     ```
   - Commit the changes.
     ```bash
     git commit -m "Add hello.txt with a greeting"
     ```

Task 5: Pushing to GitHub

9. Pushing to GitHub:
   - Push the committed changes to your GitHub repository.
     ```bash
     git push -u origin main
     ```

Task 6: Verification

10. Verify on GitHub:
    - Visit your GitHub repository in a web browser and confirm that the `hello.txt` file and commit message are visible.

