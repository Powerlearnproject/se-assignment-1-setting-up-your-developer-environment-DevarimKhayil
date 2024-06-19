#Setting Up My Developer Environment

Objective
This document outlines the steps I took to set up a developer environment for software engineering projects. The setup includes installing necessary software, configuring tools, and documenting any challenges and solutions encountered during the process.

Tasks
I. Select Your Operating System (OS)

A. I chose to use Windows 11 for this assignment.

vbnet
Copy code
  1. Download and Install Windows 11: 
     
     i. Access the Windows 11 download page: [Windows 11 Download](https://www.microsoft.com/software-download/windows11)
     
     ii. Follow the on-screen instructions to download the installation media.
     
     iii. Create a bootable USB drive or DVD using the downloaded media.
     
     iv. Restart your computer and boot from the installation media.
     
     v. Follow the installation wizard to install Windows 11 on your machine.
II. Install a Text Editor or Integrated Development Environment (IDE)

A. I selected Visual Studio Code as my IDE due to its popularity and extensive plugin support.

less
Copy code
  1. Download and Install Visual Studio Code:
     
     i. Access the Visual Studio Code download page: [Visual Studio Code Download](https://code.visualstudio.com/Download)
     
     ii. Download the installer for Windows.
     
     iii. Run the installer and follow the on-screen instructions to complete the installation.
III. Set Up Version Control System

A. I set up Git for version control and created a GitHub account for hosting repositories.

less
Copy code
  1. Install Git:
     
     i. Access the Git download page: [Git Download](https://git-scm.com/download/win)
     
     ii. Download the installer for Windows.
     
     iii. Run the installer and follow the on-screen instructions, accepting the default settings.

  2. Configure Git:
     
     i. Open Git Bash and configure your username and email:
       
       ```bash
       git config --global user.name "DevarimKhayil"
       git config --global user.email "wachirabriangeita@gmail.com"
       ```

  3. Create a GitHub Account:
     
     i. Visit GitHub: [GitHub](https://github.com)
     
     ii. Sign up for a new account by providing the required information.

  4. Initialize a Git Repository:
     
     i. Create a new directory for your project and navigate into it:
       
       ```bash
       mkdir my_project
       cd my_project
       ```
     
     ii. Initialize a Git repository:
       
       ```bash
       git init
       ```
     
     iii. Create a README file and make your first commit:
       
       ```bash
       echo "# My Project" > README.md
       git add README.md
       git commit -m "Initial commit"
       ```
     
     iv. Create a new repository on GitHub and follow the instructions to push your local repository to GitHub.
     I created a sample project initialized with Git. The repository can be accessed here; https://github.com/DevarimKhayil/Django_test.git
IV. Install Necessary Programming Languages and Runtimes

A. I installed Python as the primary programming language for this project.

less
Copy code
  1. Install Python:
     
     i. Access the Python download page: [Python Download](https://www.python.org/downloads/)
     
     ii. Download the installer for the latest version of Python.
     
     iii. Run the installer and ensure to check the box "Add Python to PATH" before clicking "Install Now."
V. Install Package Managers

A. I installed pip for Python package management.

go
Copy code
  1. Verify pip Installation:
     
     i. Open a command prompt and check if pip is installed:
       
       ```bash
       pip --version
       ```
     
     ii. If pip is not installed, you can install it using the following command:
       
       ```bash
       python -m ensurepip --upgrade
       ```
VI. Configure a Database (MySQL)

A. I chose to install MySQL for database management.

less
Copy code
  1. Download and Install MySQL:
     
     i. Access the MySQL download page: [MySQL Installer](https://dev.mysql.com/downloads/windows/installer/5.7.html)
     
     ii. Download the MySQL Installer for Windows.
     
     iii. Run the installer and follow the on-screen instructions to install MySQL, selecting the appropriate options for your setup.
VII. Set Up Development Environments and Virtualization (Optional)

A. I considered using Docker for containerization to isolate project dependencies.

less
Copy code
  1. Install Docker:
     
     i. Access the Docker download page: [Docker Desktop for Windows](https://www.docker.com/products/docker-desktop)
     
     ii. Download and install Docker Desktop, following the on-screen instructions.
     
     iii. Ensure Docker is running and verify the installation by running:
       
       ```bash
       docker --version
       ```
VIII. Explore Extensions and Plugins

A. I explored various extensions for Visual Studio Code to enhance its functionality.

less
Copy code
  1. Install Extensions in Visual Studio Code:
     
     i. Open Visual Studio Code and go to the Extensions view by clicking the Extensions icon in the Activity Bar on the side of the window.
     
     ii. Install the following extensions:
       
       a. **Python**: For Python support.
       
       b. **GitLens**: For enhanced Git capabilities.
       
       c. **Prettier**: For code formatting.
       
       d. **ESLint**: For linting JavaScript code.
IX. Document Your Setup

A. I created this document outlining the steps taken to set up the developer environment, including configurations and troubleshooting steps.

Deliverables
I. Setup Documentation

A. This document serves as the comprehensive guide detailing the setup process with step-by-step instructions.

II. GitHub Repository

A. I created a sample project initialized with Git. The repository can be accessed here.

III. Reflection on Challenges and Solutions

A. Challenges:



  1. Windows 11 Installation: Ensuring compatibility with existing hardware and software.
  
  2. Git Configuration: Understanding initial setup commands and configurations.
  
  3. MySQL Installation: Choosing the correct installer options and configurations.

B. Solutions:



  1. Windows 11: Followed the official installation guide and ensured system requirements were met.
  
  2. Git: Referred to official Git documentation for configuration commands.
  
  3. MySQL: Used default installation settings and referred to online tutorials for configuration help.

Submission
I. Submit this document and the GitHub repository link through the designated platform or email to the instructor by the specified deadline.
