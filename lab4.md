# Overview of Linux

## Definition
Open-source Unix-like operating systems first released by Linus Torvalds in 1991.

## Popular Distributions
Includes Debian, Fedora, Ubuntu, etc.

## Market Share
Dominates server market (over 96.4% of top 1 million web servers) and used in embedded systems (like Android).

## Open Source Development
Most widely-used platform for open-source software development.

## Security and Stability
Known for its secure and stable environment.

## User Interface
Primarily runs on Command Line Interface (CLI), but many distributions support Graphical User Interfaces (GUIs).

---

# Key Components

## Kernel
Core of the operating system that controls and communicates with hardware resources.

## Shell
Interface allowing users to communicate with the kernel (e.g., bash, zsh).

---

# Basic Commands

## Common Shell Commands
- `pwd`: Print working directory
- `cd`: Change directory
- `ls`: List directory contents  
  (more on `ls`, including long format)

## File Manipulation
- `cp`: Copy files  
  Example: `cp source.txt destination.txt`
  
- `mv`: Move files  
  Example: `mv oldname.txt newname.txt`
  
- `rm`: Remove files  
  Example: `rm unwantedfile.txt`
  
- `mkdir`: Create directories  
  Example: `mkdir new_directory`
  
- **Wildcards**: Used for pattern matching in commands  
  Example: `ls *.txt` (lists all `.txt` files in the directory)

---

# Example Commands
```bash
# Print the current working directory
pwd

# Change to the home directory
cd ~

# List all files and directories in long format
ls -l

# Copy a file
cp example.txt backup_example.txt

# Move a file
mv old_file.txt new_file.txt

# Remove a file
rm temporary_file.txt

# Create a new directory
mkdir project_folder

# List all .txt files in the current directory
ls *.txt
