# **Lab 1 Cheat Sheet**

## **Terminal Command Cheats**

### ***pwd*** 

The pwd command is short for print working directory and is used at any time to find out the folder we are currently in. 

### ***ls***

The ls command shows us what is in our current directroy and lists all files and folders to us. Adding a -l flag (ls -l) will provide us with more information such as recent modifications etc. Adding a -a flag with show us hidden folders too. 

### ***cd***

The cd command is used to change directory, to switch between folders. We can cd or add a tilde ~ to go back to our home directory.

### ***mkdir***

The mkdir command stands for make directory and it createes new files and folders. When creating a file using this command we need to add what type of file it is e.g. .txt .png .md .pdf etc.

### ***mv <old file> <new file>***

The mv command stands for move and this moves our files and folders from one place to another. 

### ***cp*** 

The cp command stands for copy and it copies our files and folders from one place to another.

### ***rm*** 

The rm command is our delete command, you can use rm to remove a file 

### ***rm -r***

To remove a folder, you have to use the -r flag (rm -r).

### ***rm -f***

To force delete a file.

### ***cat*** 

The cat command allows you to output the contents of a file.

### ***clear*** 

The clear comman allows you to clear the command line window.

## **Git Commands**

### ***git init <directory>***

Used to create an empty git repo in a specified directory.

### ***git status*** 

This lists which files are staged, unstage, or untracked.

### ***git add***

Stages all the changes in the directory for the next commit. Replace <directory> with a <file> to change a specific file.

### ***git commit -m "<message>"***

Commits the staged snapshot, but instead of launching a text editor, use <message> as the commit message.

### ***git remote add <name> <url>***

This creates a new connection to a remote repo. After adding a remote, you can use the <name> as a shortcut for <url> in other commands.
