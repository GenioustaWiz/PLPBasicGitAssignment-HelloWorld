1. GitHub Repository Creation

    - I logged in to my GitHub account and Openned my repositories, then clicked the green "New repository" button in the top right corner.
    - I named the repository "PLPBasicGitAssignment-HelloWorld", initialized the repository with a README file and created it.

2. Setting up Local Folder for the repository

    - I opened the file explorer and created a new folder on the computer, I named it "PLPBasicGitAssignment-HelloWorld".

3. Git Initialization

    - I opened the terminal and navigated to the newly created folder using the cd command """cd PLPBasicGitAssignment-HelloWorld""".
    - In the terminal, I ran the following command to initialize a Git repository:
    """git init""".

4. Connecting my initialized project folder to GitHub

    - I copied the URL of my GitHub repository: https://github.com/GenioustaWiz/PLPBasicGitAssignment-HelloWorld.git

    - In the terminal, I ran the following command to connect the local project to the one on GitHub:
    """git remote add origin https://github.com/GenioustaWiz/PLPBasicGitAssignment-HelloWorld.git"""

5. Creating a HelloWorld File

    - I opened VSCode IDE, I created a new text file "hello.txt", and added "Hello, Git!" text to the file.
    
6. Committing the Changes

    - In the terminal, I ran the following command to tell Git to track the changes made to the file:
    """git add hello.txt""", this "stages" the file for the next commit.
    -To create a commit with a message describing the changes, I ran the following command:
    """git commit -m 'HelloWorld'"""

7. Pushing to GitHub

    - In the terminal, I ran this command to push the committed changes to my GitHub repository:
    """git push -u origin main""".

8. Verify on GitHub

    - I opened my browser and went to my GitHub repository URL: https://github.com/GenioustaWiz/PLPBasicGitAssignment-HelloWorld and I verified that the hello.txt file is listed and the commit message is visible.