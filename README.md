# CodeCommit Git Setup

This repository contains documentation and guide for setting up a Git repository using AWS CodeCommit. This project demonstrates how to initialize a Git repository, commit and push code, and manage version control in a cloud-based environment.

## Setup Guide

1. **Create a Git Repository**
   - Go to the CodeCommit console, create a new repository, and note the repository URL.

2. **Initialize a Git Repository**
   - In your project directory, run:
     ```sh
     git init -b main
     ```

3. **Add Remote Origin**
   - Add the CodeCommit repository as the remote origin:
     ```sh
     git remote add origin <your-codecommit-repo-url>
     ```

4. **Commit and Push Code**
   - Stage, commit, and push your code:
     ```sh
     git add .
     git commit -m "Initial commit"
     git push origin main
     ```

## Key Learnings

- **Git:** A distributed version control system for tracking changes and collaborating on code.
- **Local Repository:** A version-controlled directory on your computer for managing code changes.
- **Remote Origin:** The default remote repository connected to your local Git repository for pushing and pulling changes.
- **AWS CodeCommit:** A cloud-based Git repository service for secure and scalable version control.

## Next Step

In the next part of this series, I will use AWS CodeArtifact to securely store and manage the dependencies for the project.

## Author

Kanika Mathur  
[GitHub](https://github.com/KanikaGenesis) | [LinkedIn](https://www.linkedin.com/in/kanika-mathur-083080121/)
