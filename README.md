# Holberton School Shell Projects

This repository contains all my projects related to learning and mastering shell scripting at Holberton School. The projects cover various aspects of shell scripting, including file manipulations, permissions, input/output redirections, and working with shell variables and expansions.

## Usage

1. **Clone the repository:**
   ```sh
   git clone https://github.com/holbertonschool-shell.git
   ```
2. **Navigate to a project folder:**
   ```sh
   cd holbertonschool-shell/permissions
   ```
3. **Run the scripts:**
   Each script file is executable and can be run directly from the terminal. For example, to run the `0-iam_betty` script:
   ```sh
   ./0-iam_betty
   ```
## Repository Structure

The repository is organized into the following subfolders, each representing a distinct project area:

- [permissions](#permissions)
- [io_redirections_and_filters](#io-redirections-and-filters)
- [basics](#basics)
- [init_files_variables_and_expansions](#init-files-variables-and-expansions)

## Project Descriptions

### basics

The `basics` folder introduces fundamental shell commands and scripting techniques. The tasks include:

- Navigating the filesystem.
- Viewing and manipulating files and directories.
- Understanding and using command-line utilities.

#### Notions Covered:
- Basic shell commands (`ls`, `cd`, `pwd`, `mkdir`, `rmdir`, `cp`, `mv`, `rm`).
- File viewing commands (`cat`, `more`, `less`).
- Text manipulation (`echo`, `printf`).
- Simple scripting concepts.

### permissions

The `permissions` folder contains scripts that manage and manipulate file permissions and ownership in Unix-based systems. The tasks in this project include:

- Switching users.
- Printing the current user and their groups.
- Changing file ownership and permissions.
- Creating and managing directories with specific permissions.
- Handling symbolic links and conditional ownership changes.

#### Notions Covered:
- File permissions (read, write, execute).
- User and group ownership.
- Permission representation (symbolic and numeric).
- Changing permissions and ownership with `chmod`, `chown`, and `chgrp`.

### io_redirections_and_filters

The `io_redirections_and_filters` folder focuses on manipulating the standard input/output streams and using filters to process data.

#### Notions Covered:
- Standard input (stdin), output (stdout), and error (stderr).
- Redirection operators (`>`, `>>`, `<`, `2>`, `2>&1`, etc.).
- Pipes (`|`) for chaining commands.
- Basic filters (`cat`, `head`, `tail`, `sort`, `uniq`, `grep`, `wc`, etc.).


### init_files_variables_and_expansions

The `init_files_variables_and_expansions` folder delves into shell initialization files, variables, and expansions.

#### Notions Covered:
- Shell initialization files (`.bashrc`, `.bash_profile`, etc.).
- Setting and using shell variables.
- Parameter expansion.
- Command substitution.
- Arithmetic expansion.
- Quoting and escaping characters.

