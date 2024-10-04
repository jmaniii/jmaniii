# Lab5_202133569_이정민

## Linux Command Line Basics

## 1. I/O Redirection
- **Standard Output**: Output is usually displayed on the screen but can be redirected to a file using `>` (overwrite) or `>>` (append).
- **Standard Input**: Input is from the keyboard by default, but it can be redirected from a file using `<`.
- **Combining Redirection**: Both input and output redirection can be combined in a single line (e.g., `command < input_file > output_file`).

## 2. Pipelines (`|`)
- Chains the output of one command to be the input of another. For instance: `command1 | command2`.

## 3. Expansion
- Special characters such as `*`, `?`, or `{}` expand their meanings based on the shell’s context, often used for file pattern matching or variable expansion.

## 4. Backslash (`\`)
- Used to escape special characters or to split a long command across multiple lines, ensuring it is interpreted as a single command.

## 5. File Permissions
- **Linux Permissions**: Files and directories have three types of permissions (read `r`, write `w`, execute `x`) for three categories of users: owner, group, and others.
    - **Changing Permissions**: Use `chmod` to modify permissions. For example, `chmod 644 file.txt` grants read/write permission to the owner and read-only to others.
    - **Numerical permission codes**: Numerical codes (e.g., 644) represent binary permissions: `6 = rw-`, `4 = r--`.

## 6. Superuser (Root)
- The superuser (`root`) has full system administration privileges. Precede a command with `sudo` to run it as a superuser.
- To exit a superuser session, use the `exit` command.

## 7. Text Editors
- **CLI-based**: Editors like `nano` or `vim` are used directly from the command line.
- **GUI-based**: Graphical editors are also available, though they’re more suited for desktop environments.

## 8. Shell Scripts
- A shell script is a sequence of shell commands saved in a file, usually with a `.sh` extension.
    - **Writing a Shell Script**: Create a script using a text editor (e.g., `nano script.sh`), starting with a shebang (`#!/bin/bash`), followed by commands to be executed.
    - **Running a Shell Script**: Grant execute permission with `chmod +x script.sh`, and then run it with `./script.sh`.

## 9. Command History
- The `history` command lists previously executed commands. You can also save the history to a file (e.g., `history > history.txt`).

## 10. Common Commands
- **wget**: Downloads files from the internet.
- **curl**: Transfers data using URLs. 
- **grep**: Searches for text patterns within files.

## 11. Shell Scripting Tips
-**Variables**: Assign values using variable=value (no spaces). Access variables with $variable.
-**Conditionals**: Use if statements to perform conditional execution.
```bash
if [ -f "file.txt" ]; then
  echo "File exists."
		else
  echo "File does not exist."
		fi
```
-**Loops**: Use for, while, or until loops to repeat tasks.
```bash
for i in {1..5}; do
    echo "Iteration $i"
done
```

