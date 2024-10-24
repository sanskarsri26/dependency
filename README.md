# Project Dependency Installation Guide

This guide will walk you through the installation of the necessary dependencies for the project, including Python and additional libraries.

## Prerequisites

Before installing the dependencies, ensure that you have administrative rights on your machine.

## Step 1: Install Python

### Windows:

1. Go to the [official Python website](https://www.python.org/downloads/).
2. Download the latest version of Python.
3. Run the installer and ensure to check the box that says **"Add Python to PATH"** during installation.
4. Click **Install Now** and follow the on-screen instructions.

### macOS:

1. Open the Terminal.
2. Install Homebrew if it's not already installed by running:
   ```bash
   /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
Install Python using Homebrew:
bash
Copy code
brew install python
Linux:
Most Linux distributions come with Python pre-installed. To check if Python is installed, open the terminal and run:

bash
Copy code
python3 --version
If Python is not installed, you can install it using your package manager. For Debian-based systems, run:

bash
Copy code
sudo apt-get update
sudo apt-get install python3
Step 2: Install Project Dependencies
The project requires the following dependencies:

PyQt5: A set of Python bindings for the Qt application framework.
SQLite3: A database management system.
DB Browser for SQLite: A visual tool to manage SQLite databases.
Run the following command in your terminal or command prompt to install the dependencies based on your operating system.

For Linux:
Open a terminal.
Run the following command to install the dependencies:
bash
Copy code
python3 install_dependencies.py
For macOS:
Open a terminal.
Run the following command to install the dependencies:
bash
Copy code
python3 install_dependencies.py
For Windows:
Open Command Prompt as Administrator.
Run the following command to install the dependencies:
bash
Copy code
python install_dependencies.py
Step 3: Verify Installation
To verify that the dependencies are installed correctly, you can run the following commands:

For Python:
bash
Copy code
python --version  # or python3 --version
For PyQt5:
bash
Copy code
python -m pip show pyqt5
For SQLite3:
bash
Copy code
sqlite3 --version
For DB Browser for SQLite:
Open the application from your applications menu or by running:

bash
Copy code
sqlitebrowser
Conclusion
Once you have completed these steps, you should have all the necessary dependencies installed. You can now run the project and start using the features provided.

If you have any questions or run into issues, feel free to reach out for assistance.
