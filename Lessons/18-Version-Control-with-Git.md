# Lesson 18: Version Control with Git

## Introduction to Git and GitHub

### What is Git?

Git is a distributed version control system that allows you to track changes in your code and collaborate with others. It helps you manage your project history, revert to previous versions, and work on different features simultaneously without affecting the main codebase.

### What is GitHub?

GitHub is a web-based platform that uses Git for version control and collaboration. It allows you to host your repositories online, making it easy to share your code with others, collaborate on projects, and contribute to open-source software.

### Why Use Git and GitHub?

- **Version Tracking**: Keep a history of changes made to your code, allowing you to revert to previous versions if necessary.
- **Collaboration**: Work with others on the same project without overwriting each other's changes.
- **Backup**: Host your code in the cloud, ensuring you have a backup of your work.
- **Showcase Your Work**: Share your projects with potential employers or collaborators.

## Basic Commands and Workflows

### Setting Up Git

1. **Install Git**: Download and install Git from [git-scm.com](https://git-scm.com/).
2. **Configure Git**: Set your username and email, which will be associated with your commits.

   ```bash
   git config --global user.name "Your Name"
   git config --global user.email "you@example.com"
   ```

### Creating a New Repository

1. **Initialize a Repository**: Navigate to your project folder in the terminal and run:

   ```bash
   git init
   ```

2. **Add Files**: Stage your files for commit.

   ```bash
   git add .
   ```

3. **Commit Changes**: Save your changes with a descriptive message.

   ```bash
   git commit -m "Initial commit"
   ```

### Working with GitHub

1. **Create a Repository on GitHub**: Go to [GitHub](https://github.com/) and create a new repository.

2. **Link Your Local Repository to GitHub**: Copy the repository URL and run the following command in your terminal:

   ```bash
   git remote add origin https://github.com/username/repository.git
   ```

3. **Push Changes to GitHub**: Upload your local commits to GitHub.

   ```bash
   git push -u origin main
   ```

### Basic Git Commands

Here are some essential Git commands you will frequently use:

- **Check Status**: See the status of your repository and staged files.

  ```bash
  git status
  ```

- **View Commit History**: View the commit history of your repository.

  ```bash
  git log
  ```

- **Create a New Branch**: Create a new branch for a feature or fix.

  ```bash
  git branch new-feature
  ```

- **Switch to a Branch**: Change to a different branch.

  ```bash
  git checkout new-feature
  ```

- **Merge a Branch**: Merge changes from one branch into another.

  ```bash
  git checkout main
  git merge new-feature
  ```

- **Pull Changes from GitHub**: Update your local repository with changes from GitHub.

  ```bash
  git pull origin main
  ```

### Example Workflow

1. **Start a New Project**:

   - Initialize a new Git repository.
   - Create your project files and make your first commit.

2. **Create a New Feature**:

   - Create a new branch for the feature you are working on.
   - Make changes, stage them, and commit them to the new branch.

3. **Merge Changes**:

   - Switch back to the main branch.
   - Merge your feature branch into the main branch.

4. **Push to GitHub**:
   - Push your changes to the remote repository on GitHub.

### Conclusion

By using Git and GitHub, you can effectively manage your code, collaborate with others, and maintain a history of your projects. Familiarizing yourself with basic commands and workflows will greatly enhance your development process and make it easier to work on larger projects.

---

This lesson provides a foundational understanding of version control with Git and GitHub, preparing you to utilize these tools effectively in your web development projects.

[Next: 19-Final-Project](./19-Final-Project.md)
