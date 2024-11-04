Project Report Summary: Basic Linux Commands Project with GitHub Integration
Introduction:
Project showcases fundamental Linux commands, Git version control, and GitHub integration.
Key objectives include directory structure organization, scripting, and secure GitHub authentication.
Objectives:
Learn basic Linux commands for directory management and file handling.
Create and manage a Python script in an organized project structure.
Utilize Git for version control with commit and staging capabilities.
Securely push code to GitHub using both HTTPS with PAT and SSH authentication.
Tools and Technologies:
Operating System: Ubuntu
Version Control System: Git
Code Hosting Platform: GitHub
Programming Language: Python 3
Workflow:
Create Project Structure:

Directory setup using mkdir to separate source code (src) and project files.
Simple "Hello, World!" script written and saved in src/hello.py.
Initialize Git Repository:

git init to initialize a new Git repository.
Configured user details for Git.
Stage and Commit Files:

Used git add . to stage files and git commit to record changes.
Link and Push to GitHub:

Created a GitHub repository, set as remote with git remote add origin <URL>.
Pushed code securely using PAT for HTTPS or SSH key authentication.
Authentication Challenges:

Issue: GitHub no longer supports password-based authentication.
Solution 1: Generated and used a Personal Access Token (PAT).
Solution 2: Configured SSH key-based authentication as an alternative.
Key Commands and Explanations:
Linux Commands: mkdir, cd, ls, cat for directory and file management.
Git Commands: git init, git add, git commit, git remote, git push for version control.
Lessons Learned:
Linux commands are crucial for efficient file management.
Git and GitHub are essential tools for code tracking and collaboration.
PATs and SSH keys are needed for secure GitHub access.
Future Work:
Explore advanced Linux commands and scripting.
Add automation scripts for enhanced functionality.
Set up Continuous Integration (CI) using GitHub Actions.
