# Git Basics

## Importance of Version Control
Version control systems are essential for managing changes in software development and documentation. The basic approach—making multiple copies of files—can quickly become unmanageable (e.g., multiple versions of a file named "project_final.txt"). Git provides a more systematic method for version control and collaboration.

## Snapshots vs. Changes
There are two methods to track changes:
- **Changes**: Only stores the differences made to the original file.
- **Snapshots**: Stores the complete state of the file at different points in time.

## Types of Version Control Systems
1. **Local Version Control**: Versioning done on a single developer's computer.
2. **Centralized Version Control**: A single server hosts all the version history.
3. **Distributed Version Control** (used by Git): Every developer has a complete copy of the project history on their machine.

## Git’s Three States
Files in Git can be in one of three states:
- **Modified**: Files that have been changed but not yet staged.
- **Staged**: Files that are marked for inclusion in the next commit.
- **Committed**: Changes have been saved in the local repository.

## Installing Git
Git can be installed on various operating systems:
- **Linux**: Use the terminal for installation on Debian-based distributions.
- **Windows**: Use Git Bash.
- **Mac**: Download Git from the official website.

## Git Configuration
Git configurations can be set at three levels:
1. **System**: Applies to every user and repository on the system.
2. **Global**: Affects all repositories for a single user.
3. **Local**: Specific to a single repository.

## Basic Git Commands

- **Initialize a Repository**:  
  ```bash
  $ git init
```
- **Check Repository Status**:
  ```bash
$ git status
```
- **Stage a File**:
  ```bash
$ git add [file_name]
```
- **Unstage a File**:
  ```bash
$ git rm --cached [file_name]
```
- **Commit Changes**:
```bash
$ git commit -m "commit message"
```
