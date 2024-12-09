# git-usage-guide

### Description:
</br>
This repository contains a step-by-step guide for using Git and uploading projects to GitHub. It is designed for beginners or anyone who needs a quick reference for frequently used Git commands.

### Getting Started: Git and GitHub Setup
1. Check Git Installation
- Verify if Git is installed:

       git --version

 If not installed, download it from the [official Git website](https://git-scm.com/)

2.  Configure User Information
- Set your username and email address for Git:


       git config --global user.name "Your Name"
       git config --global user.email "email@example.com"

3. Configure Line Endings (Recommended for Windows)
- To ensure proper line-ending conversions:

       git config --global core.autocrlf true

### Uploading a New Project to GitHub
1. Initialize Git
Start Git in your project directory and make the first commit:

       git init
       git add .
       git commit -m "Initial commit"
   
3. Create a New Repository on GitHub
- Log in to your GitHub account.
- Click the "+" icon in the top-right corner, then select New repository.
- Enter a repository name (e.g., my-first-project) and click Create repository.
4. Add a Remote Repository
Copy your repository URL from GitHub (e.g., https://github.com/username/my-first-project.git), and link it as a remote:

       git remote add origin https://github.com/username/my-first-project.git
4. Push Your Code
Send your project to GitHub:


       git branch -M main
       git push -u origin main

