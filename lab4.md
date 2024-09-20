# Lab4_202133569_이정민


## Linux

- **Definition**: An open-source operating system similar to Unix.
- **Usage**: Commonly used for servers; over 96.4% of the top 1 million web servers run on Linux.
- **Distributions**: Popular versions include Debian, Fedora, and Ubuntu.
- **Characteristics**: Known for security, stability, and support for open-source software development.
- **Interface**: Primarily operates via CLI, but many distributions also support GUIs.

## Kernel and Shell

- **Kernel**: Core of the operating system managing hardware resources.
- **Shell**: Interface for users to communicate with the kernel (e.g., bash, zsh).

## CLI vs GUI

| Feature             | CLI                                  | GUI                                   |
|---------------------|--------------------------------------|---------------------------------------|
| Operation           | Requires command memorization        | Intuitive, mouse-operated             |
| Speed               | Faster for experienced users         | Slower compared to CLI                |
| Automation          | Supports scripts for automation      | Manual steps required for repetitive tasks |
| User Base           | Developers and advanced users        | Daily users                           |

## Running a Shell Terminal

- **Linux/macOS**: Search for "Terminal" in applications.
- **Windows**: Install "Git Bash" for shell terminal access.

## Basic Shell Commands

| Command          | Description                                           |
|------------------|-------------------------------------------------------|
| `pwd`            | Displays the current working directory                 |
| `cd`             | Changes the current directory                           |
| `ls`             | Lists files and directories in the current directory   |
| `ls /bin`       | Lists files in the `/bin` directory                    |
| `ls -l`         | Long format listing of files (permissions, owner, etc.) |
| `clear`         | Clears the terminal screen                              |
| `help`          | Displays a list of built-in commands                   |

## Path Types

- `/[directory]`: Absolute path
- `./[directory]`: Relative path (current directory)
- `../[directory]`: Relative path (parent directory)
- `~`: Home directory of the current user

## File Manipulation Commands

| Command                   | Description                                  |
|---------------------------|----------------------------------------------|
| `cp file1 file2`         | Copies contents of `file1` into `file2`    |
| `cp -R dir1 dir2`        | Recursively copies contents of `dir1` to `dir2` |
| `mv file1 file2`         | Renames `file1` to `file2`                  |
| `rm file`                 | Permanently deletes `file`                   |
| `mkdir directory_name`    | Creates a new directory                      |

## Wildcards

- `*`: Matches all files
- `g*`: Matches files starting with "g"
- `b*.txt`: Matches files starting with "b" and ending with ".txt"
- `Data???`: Matches files starting with "Data" followed by exactly 3 characters

## Caution

- **Deletion Warning**: Use caution with `rm`, as files deleted this way cannot be recovered. It's advisable to test commands with `ls` first to see which files would be affected.

## Help and Exiting

| Command             | Description                                     |
|---------------------|-------------------------------------------------|
| `help`              | Displays built-in commands                      |
| `man [command]`     | Displays the manual for the specified command    |
| `exit`              | Closes the terminal session                      |
