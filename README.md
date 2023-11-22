# How to Command Line/Terminal for Git

> Note: Command Line and Terminal refer to the same basic thing. Shell is another similar term.

## 1. Understanding the Command Line
- The terminal or command line is a text interface for interacting with your computer.
- Learning to open it, navigate directories, list contents, and execute commands is crucial.
- It’s essential for using Git and managing files and directories.

## 2. How to Open the Terminal
- **Windows:** Use "Command Prompt" or "PowerShell" from the Start menu.
- **macOS:** Find "Terminal" in Applications > Utilities.
- **Linux:** Open "Terminal" from your applications menu or launcher.

## 3. Navigating Between Directories with `cd`
- Directories are like folders.
- Change directories with `cd [directory-path]`.
  - Example: `cd Documents/GitProjects` to enter the GitProjects folder in Documents.
- To go up one level, use `cd ..`

## 4. Listing Files and Folders with `ls` (and Alternatives)
- To see what's in the current directory:
  - **macOS/Linux:** Use `ls`.
  - **Windows:** Use `dir` in Command Prompt or `ls` in PowerShell.
- Example: Typing `ls` and pressing Enter will list all files and folders in your current directory.

## 5. Creating New Files with `touch`
- Use `touch [filename]` to create a new empty file.
  - Example: `touch readme.md` creates a file named 'readme.md'.

## 6. Creating New Directories with `mkdir`
- Use `mkdir [directory-name]` to create a new directory.
  - Example: `mkdir MyNewProject` creates a directory named 'MyNewProject'.

## 7. Executing Commands
- Type your command and press Enter to execute it.
- To check Git installation, type `git --version` and press Enter.

## 8. Verifying Git Installation
- Type `git --version` in your terminal.
- If Git is installed, it will show the version number.
- If not, you’ll get an error, indicating Git is not installed.
