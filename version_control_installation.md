### Setting Up Version Control System with Git and GitHub

1. **Install Git**:
   - **Windows**: Download the Git installer from the [Git for Windows](https://gitforwindows.org/) site. Run the installer and follow the on-screen instructions, accepting the default options unless you have specific requirements.

2. **Configure Git**:
   - Open a terminal or command prompt.
   - Set your Git username and email (this information will be associated with your commits):
     ```bash
     git config --global user.name "Your Name"
     git config --global user.email "your.email@example.com"
     ```

3. **Create a GitHub Account**:
   - Go to the [GitHub website](https://github.com).
   - Sign up for a new account by providing a username, email, and password.
   - Verify your email address to activate your account.

4. **Create a New Repository on GitHub**:
   - Once logged in, click the `+` icon in the upper-right corner and select "New repository."
   - Fill in the repository name, description (optional), and choose whether it will be public or private.
   - Click "Create repository."

5. **Initialize a Git Repository Locally**:
   - Navigate to the directory where you want to create your project.
   - Initialize a new Git repository:
     ```bash
     git init
     ```
   - Add your project files to the repository:
     ```bash
     git add .
     ```
   - Commit the files to the repository:
     ```bash
     git commit -m "Initial commit"
     ```

6. **Connect Your Local Repository to GitHub**:
   - Copy the URL of your GitHub repository (it will be something like `https://github.com/giusmahnn/helloworld`).
   - Add the remote URL to your local Git repository:
     ```bash
     git remote add origin https://github.com/giusmahnn/helloworld
     ```
   - Push your local commits to the GitHub repository:
     ```bash
     git push -u origin master
     ```

7. **Make Your First Commit**:
   - Edit or add new files to your project.
   - Stage the changes for commit:
     ```bash
     git add .
     ```
   - Commit the changes:
     ```bash
     git commit -m "Description of changes"
     ```
   - Push the changes to the remote repository:
     ```bash
     git push
     ```

Troubleshooting:
* Ensure SSH keys are set up correctly if facing authentication issues.