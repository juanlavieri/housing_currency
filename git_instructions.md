Creating branches in Git for collaborative work is a great way to manage different aspects of a project simultaneously. Since each of you will work on a different currency, you can create separate branches for gold prices, Bitcoin, and the U.S. dollar. I'll walk you through the process step-by-step.

### Initial Setup
1. **Clone the Repository**: If you haven't already, clone the main repository to your local machine. Use the command:
   ```bash
   git clone [repository URL]
   ```
   Replace `[repository URL]` with the URL of your repository.

2. **Navigate to the Repository Directory**: Use the command:
   ```bash
   cd [repository name]
   ```
   Replace `[repository name]` with the name of your repository.

### Creating Branches
Each of you will create a branch for your respective currency.

3. **Create a New Branch**:
   - For Gold Prices:
     ```bash
     git checkout -b gold-prices
     ```
   - For Bitcoin:
     ```bash
     git checkout -b bitcoin-prices
     ```
   - For the U.S. Dollar:
     ```bash
     git checkout -b dollar-value
     ```

   The `git checkout -b [branch-name]` command creates a new branch and switches to it.

4. **Confirm Branch Creation**: Use `git branch` to list all branches and confirm that you're on the correct branch.

### Working on Your Branch
5. **Make Changes**: Edit, add, and modify files as needed for your part of the project.

6. **Commit Changes**:
   - Stage your changes:
     ```bash
     git add .
     ```
   - Commit your changes:
     ```bash
     git commit -m "Descriptive message about the changes"
     ```

7. **Push Changes to GitHub**:
   - The first time you push your branch, use:
     ```bash
     git push --set-upstream origin [branch-name]
     ```
   - For subsequent pushes, just use:
     ```bash
     git push
     ```

### Collaborating and Merging
8. **Pull Requests**: Once you're done with your changes on your branch, create a pull request on GitHub. This is where team members can review the changes.

9. **Code Review and Merge**: After review, if everything looks good, the branch can be merged into the main branch.

10. **Keep Your Branch Updated**: Regularly update your branch with any changes from the main branch to avoid conflicts. Use:
    ```bash
    git pull origin main
    ```

### Finalizing the Project
11. **Final Merge**: Once all individual parts are complete and reviewed, merge each branch into the main branch, one at a time. This is typically done via pull requests on GitHub.

12. **Delete Branches (Optional)**: After successful merges and completion of the project, you can delete the branches to keep the repository clean.

Remember, clear and frequent communication among team members is crucial in a collaborative project to avoid merge conflicts and redundant work. Good luck with your project!