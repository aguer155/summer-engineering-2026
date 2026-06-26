# Git

git status
Shows changed files.

git add file
Stages one file.

git commit -m ""
Creates a commit.

git push
Uploads commits.

git pull
Downloads changes.

git checkout branch
Switches branches.

# Linux Cheat Sheet

## Navigation

| Command          | Purpose                                                           |
| ---------------- | ----------------------------------------------------------------- |
| `pwd`            | Show my current directory.                                        |
| `ls`             | List files and folders in the current directory.                  |
| `ls -la`         | List all files, including hidden ones, with detailed information. |
| `cd <directory>` | Change directories.                                               |
| `cd ..`          | Move up one directory.                                            |
| `cd ~`           | Go to my home directory.                                          |
| `clear`          | Clear the terminal screen.                                        |

---

## File & Directory Management

| Command                     | Purpose                                                         |
| --------------------------- | --------------------------------------------------------------- |
| `mkdir <folder>`            | Create a new directory.                                         |
| `touch <file>`              | Create a new empty file.                                        |
| `cp <source> <destination>` | Copy a file.                                                    |
| `mv <source> <destination>` | Move or rename a file/folder.                                   |
| `rm <file>`                 | Delete a file.                                                  |
| `rm -r <folder>`            | Delete a folder and everything inside it. *(Use with caution!)* |
| `cat <file>`                | Display the contents of a file.                                 |

---

## Searching

| Command                | Purpose                                                                |
| ---------------------- | ---------------------------------------------------------------------- |
| `find <path>`          | Find files and directories.                                            |
| `find . -name "*.txt"` | Find all `.txt` files in the current directory and its subdirectories. |

---

## Help

| Command            | Purpose                              |
| ------------------ | ------------------------------------ |
| `man <command>`    | Open the manual page for a command.  |
| `<command> --help` | Show help information for a command. |

---

## Vim Basics

| Command        | Purpose              |
| -------------- | -------------------- |
| `vim file.txt` | Open a file in Vim.  |
| `i`            | Enter Insert mode.   |
| `Esc`          | Leave Insert mode.   |
| `:w`           | Save.                |
| `:q`           | Quit.                |
| `:wq`          | Save and quit.       |
| `:q!`          | Quit without saving. |

---

## Things to Remember

* `~` = Home directory
* `.` = Current directory
* `..` = Parent directory
* `PATH` = List of directories the shell searches for executables
