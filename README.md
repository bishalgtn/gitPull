#Git pull

Git pull is a command used in Git version control to update your local repository with the latest changes from a remote repository. When collaborating on a project, others may have pushed changes to the remote repository, and by running git pull, you can fetch and merge those changes into your local working directory. This helps you stay in sync with the project's development, ensuring you have the most up-to-date code before continuing your work.

##The git pull command serves two main purposes:

**Fetching new changes:** It downloads the latest commits from the remote repository, ensuring that your local repository is up to date.
**Merging:** After fetching the changes, git pull will automatically merge the changes into your local branch, which is crucial for collaborating with other developers.

Without regularly using git pull, your local repository might fall behind, causing conflicts when you eventually try to push your changes, or even potentially working with outdated code.


##Steps to pull git repo to local System

Open your terminal: Navigate to your project directory using a terminal (or command prompt on Windows).

Check your current branch: Ensure that you're working on the correct branch by running git branch. If you need to switch to a specific branch, use git checkout <branch-name>.

Run git pull: In your terminal, run the command:
```bash
git pull origin <branch-name>
```

Resolve any merge conflicts: If there are conflicting changes between your local and remote repository, Git will notify you of the conflict and ask you to resolve it. After resolving conflicts, commit the changes.

Review the changes: Once the pull completes, you can review the changes by checking the commit log or using git status