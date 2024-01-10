# Handy Terminal Commands

## General Information
This guide covers basic yet essential terminal commands used in Bash, which is common across MacOS, Linux, and Git Bash for Windows. These commands are fundamental for navigating and manipulating the file system, and for general system interaction.

## Commands

### `ls` - List Files and Directories
- **Usage**: `ls [options] [directory]`
- **Default**: Lists files and directories in the current directory.
- **Options**:
  - `-a`: Show all files and folders, including hidden ones (those starting with a `.`).
  - `-l`: List in long format, showing permissions, ownership, size, and modification date.
  - `-h`: With `-l`, shows file sizes in human-readable format (e.g., KB, MB).
  - `-t`: Sort by time modified (newest first).

### `cd` - Change Directory
- **Usage**: `cd [directory]`
- **Default**: Changes the current directory to the specified one.
- **Special Directories**:
  - `cd ~` or `cd`: Changes to the home directory.
  - `cd ..`: Moves up one directory level.
  - `cd -`: Changes to the previous directory.

### `pwd` - Print Working Directory
- **Usage**: `pwd`
- **Function**: Displays the path of the current working directory.

### `mkdir` - Make a New Directory
- **Usage**: `mkdir [directory]`
- **Function**: Creates a new directory with the specified name.
- **Options**:
  - `-p`: Create parent directories as needed (makes intermediate directories).

### `rm` - Remove Files or Directories
- **Usage**: `rm [options] [file/directory]`
- **Function**: Deletes files or directories.
- **Options**:
  - `-r`: Recursive, removes directories and their contents.
  - `-f`: Force, ignores nonexistent files and arguments, never prompts.
  - `-i`: Interactive, prompts before every removal.

### `cp` - Copy Files or Directories
- **Usage**: `cp [options] [source] [destination]`
- **Function**: Copies files or directories.
- **Options**:
  - `-r`: Recursive, copies directories and their contents.
  - `-i`: Interactive, prompts before overwrite.
  - `-v`: Verbose, shows files as they are copied.

### `mv` - Move or Rename Files or Directories
- **Usage**: `mv [options] [source] [destination]`
- **Function**: Moves/renames files or directories.
- **Options**:
  - `-i`: Interactive, prompts before overwrite.
  - `-v`: Verbose, shows files as they are moved.

### `cat` - Concatenate and Display Files
- **Usage**: `cat [file]`
- **Function**: Displays the content of the file on the terminal.
- **Options**:
  - `-n`: Number all output lines.

### `grep` - Search Text Using Patterns
- **Usage**: `grep [options] [pattern] [file]`
- **Function**: Searches for a specified pattern in a file and prints the matching lines.
- **Options**:
  - `-i`: Ignore case distinctions.
  - `-v`: Invert match, show lines that do not match.
  - `-r`: Recursive, search through directories.

### `echo` - Display a Line of Text
- **Usage**: `echo [string]`
- **Function**: Outputs the given string to the terminal.

### `man` - Manual Pages
- **Usage**: `man [command]`
- **Function**: Displays the manual page for the specified command.

## Tips
- Most commands have a `--help` option that displays brief usage information.
- Use the `man` command to access detailed information about a command.
- Combining commands with pipes (`|`) and redirection (`>`, `>>`) can be very powerful.

Feel free to experiment and explore these commands to get a better understanding of how they work in your specific environment.
