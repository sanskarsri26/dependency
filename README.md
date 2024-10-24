Here's the complete installation guide in Markdown format, ready to be copied into your `README.md` file:

```markdown
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
   ```
3. Install Python using Homebrew:
   ```bash
   brew install python
   ```

### Linux:

Most Linux distributions come with Python pre-installed. To check if Python is installed, open the terminal and run:
```bash
python3 --version
```
If Python is not installed, you can install it using your package manager. For Debian-based systems, run:
```bash
sudo apt-get update
sudo apt-get install python3
```

## Step 2: Install Project Dependencies

The project requires the following dependencies:
- **PyQt5**: 
- **SQLite3**:
- **DB Browser for SQLite**: 

Run the following command in your terminal or command prompt to install the dependencies based on your operating system.

### For Linux:

1. Open a terminal.
2. Run the following command to install the dependencies:
   ```bash
   python3 install_dependencies.py
   ```

### For macOS:

1. Open a terminal.
2. Run the following command to install the dependencies:
   ```bash
   python3 install_dependencies.py
   ```

### For Windows:

1. Open Command Prompt as Administrator.
2. Run the following command to install the dependencies:
   ```bash
   python install_dependencies.py
   ```

## Step 3: Verify Installation

To verify that the dependencies are installed correctly, you can run the following commands:

### For Python:
```bash
python --version  # or python3 --version
```

### For PyQt5:
```bash
python -m pip show pyqt5
```

### For SQLite3:
```bash
sqlite3 --version
```

### For DB Browser for SQLite:
Open the application from your applications menu or by running:
```bash
sqlitebrowser
```

## Conclusion

Once you have completed these steps, you should have all the necessary dependencies installed. You can now run the project and start using the features provided.

Feel free to reach out for assistance if you have any questions or run into issues.
```
