[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/vbnbTt5m)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15277471&assignment_repo_type=AssignmentRepo)
# Dev_Setup
Setup Development Environment

#Assignment: Setting Up Your Developer Environment

#Objective:
This assignment aims to familiarize you with the tools and configurations necessary to set up an efficient developer environment for software engineering projects. Completing this assignment will give you the skills required to set up a robust and productive workspace conducive to coding, debugging, version control, and collaboration.

#Tasks:

1. Select Your Operating System (OS):
   Choose an operating system that best suits your preferences and project requirements. Download and Install Windows 11. https://www.microsoft.com/software-download/windows11
Go to the Windows 11 Download Page:
Download Windows 11
Follow the Instructions:
Click on "Download Now" to download the Installation Assistant.
Run the Installation Assistant and follow the on-screen instructions to upgrade to Windows 11.

2. Install a Text Editor or Integrated Development Environment (IDE):
   Select and install a text editor or IDE suitable for your programming languages and workflow. Download and Install Visual Studio Code. https://code.visualstudio.com/Download
   Go to the Visual Studio Code Download Page:
Download Visual Studio Code
Download and Install:
Select the version that suits your operating system. In this case, select the one supporting Windows.
Run the installer and follow the setup instructions.

3. Set Up Version Control System:
   Install Git and configure it on your local machine. Create a GitHub account for hosting your repositories. Initialize a Git repository for your project and make your first commit. https://github.com
o to the Git Download Page.
Download the installer and follow the setup instructions.
Set up Git:
Open Git Bash and configure your username and email:
bash
Copy code
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"
Create a GitHub Account:
Go to GitHub and create a new account.
Initialize a Git Repository:
Open your project directory in Git Bash:
bash
Copy code
mkdir my_project
cd my_project
git init
Make your first commitment:
bash
Copy code
echo "# My Project" > README.md
git add README.md
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/yourusername/my_project.git
git push -u origin main

4. Install Necessary Programming Languages and Runtimes:
  Instal Python from http://wwww.python.org programming language required for your project and install their respective compilers, interpreters, or runtimes. Ensure you have the necessary tools to build and execute your code.Go to the Python Download Page.
Download the installer and run it. Make sure to select "Add Python to PATH" during the installation.
Check Installation:
Open the Command Prompt and type:
bash
Copy code
python --version
pip --version

5. Install Package Managers:
   If applicable, install package managers like pip (Python).Make sure pip is installed.
pip comes with Python. Check in with:
bash
Copy code
pip --version
   
6. Configure a Database (MySQL):
   Download and install MySQL database. https://dev.mysql.com/downloads/windows/installer/5.7.html
i. Go to the MySQL Installer Page.
ii. Download and Run the installer.
iii. Follow the setup instructions; you can choose which configuration best suits you.

7. Set Up Development Environments and Virtualization (Optional):
   Consider using virtualization tools like Docker or virtual machines to isolate project dependencies and ensure consistent environments across different machines.
Getting started with Docker:
i. Go to the Docker Download Page.
ii. Download and Install Docker Desktop for Windows.
iii. Follow the setup instructions.

8. Explore Extensions and Plugins:
   Explore available extensions, plugins, and add-ons for your chosen text editor or IDE to enhance functionality, such as syntax highlighting, linting, code formatting, and version control integration.
Visual Studio Code Extensions,
Open Visual Studio Code.
Go to the Extensions view by clicking the Extensions icon in the Activity Bar on the side of the window.
Search and install recommended extensions like Python, GitLens, Prettier and many more.

12. Document Your Setup:
    Create a comprehensive document outlining the steps you've taken to set up your developer environment. Include any configurations, customizations, or troubleshooting steps encountered during the process. 

#Deliverables:
- Document detailing the setup process with step-by-step instructions and screenshots where necessary.
- A GitHub repository containing a sample project initialized with Git and any necessary configuration files (e.g., .gitignore).
- A reflection on the challenges faced during setup and strategies employed to overcome them.

#Submission:
Submit your document and GitHub repository link through the designated platform or email to the instructor by the specified deadline.

#Evaluation Criteria:**
- Completeness and accuracy of setup documentation.
- Effectiveness of version control implementation.
- Appropriateness of tools selected for the project requirements.
- Clarity of reflection on challenges and solutions encountered.
- Adherence to submission guidelines and deadlines.

Note: Feel free to reach out for clarification or assistance with any aspect of the assignment.
