## Kernel and Shell

- **Kernel**: The core of the OS, controlling hardware resources.
- **Shell**: Interface for user-kernel communication (e.g., bash, zsh).
- **Shell Usage**: Users run applications and give commands through the shell.

### Linux

-Open-source Unix-like operating systems and kernels, first released by Linus Torvalds in 1991  
-Popular distributions include Debian,Fedora,and Ubuntu,among many others  
-Leading OS on servers (over 96.4% of the top 1 million web servers)  
-Also runs on embedded systems and mobile systems (Android)  
-Most widely-used platform for open source software development  
-Secure and stable  
-Runs on CLI,but many distributions support GUIs as well

## CLI vs GUI

| CLI (Command Line Interface)         | GUI (Graphical User Interface)          |
| ------------------------------------ | --------------------------------------- |
| Requires remembering commands        | Easy and intuitive to use               |
| Mostly keyboard-based                | Mouse-driven with some keyboard shortcuts|
| Fast, supports automation and scripts| Slower, requires manual work            |
| Essential for developers             | Better suited for daily users           |

# Shell Command
- **pwd**: Shows the directory currently working on.
- **cd**: Change directory.
- **ls**: Shows the subfiles and directories of the directory currently working on.

### Manipulation
- **cp**: Copy files and directories.
	- **cp file1 file2**: Copy the contents of file1 to file2.
	- **cp file1 dir1**: Copy file1 into dir1.
	- **cp -R dir1 dir2**: Copy the contents of the dir1.
	
- **mv**: Move files and directories or rename them.
	- **mv file1 file2**: If file2 exists, replace the contents of file1; otherwise, the file1 is renamed file2.
	- **mv file1 file2 dir1**: File1 and file2 are moved to dir1 and if dir1 does not exist, an error appears.
	- **mv dir1 dir2**:  If dir2 exists, dir1 is moved within dir2; otherwise, the dir1 is renamed dir2.

- **rm**: Delete files and directories **permantely**.
	- **rm file1 file2**: Delete file1 and file2.
	- **rm -r dir1 dir2**: Delete dir1 and dir2. If there is no -r, an error appears.

- **mkdir**: Make a new directory
	
- **Wildcards**
	- '*' : All file names
	- a*.txt: All file names that begin with the character "a" and end with the characters ".txt"
	- 'Data???': Any file name that begins with the characters "Data" followed by exactly 3 characters

 - ## Exiting the Terminal

- **exit**: Closes the terminal session.
