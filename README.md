# Lingua Franca CLI Tasks

This project demonstrates a series of tasks performed using the **Command Line Interface (CLI)**. The tasks showcase skills in navigating and managing the file system, redirecting input and output, manipulating files, and configuring the CLI environment.

## Table of Contents

- [Project Overview](#project-overview)
- [Skills Demonstrated](#skills-demonstrated)
- [Project Structure](#project-structure)
- [Task Groups](#task-groups)
  - [1. Navigating the File System](#1-navigating-the-file-system)
  - [2. Viewing and Changing the File System](#2-viewing-and-changing-the-file-system)
  - [3. Redirecting Input and Output](#3-redirecting-input-and-output)
  - [4. Configuring the Environment](#4-configuring-the-environment)
- [Usage](#usage)
- [Conclusion](#conclusion)


## Project Overview

This repository contains the completed tasks from the **Lingua Franca** project, designed to enhance command-line skills. It involves working with a file system containing language files grouped by continent, as well as configuring the terminal environment for productivity.

## Skills Demonstrated

- Navigating file systems with commands like `cd` and `ls`.
- File and directory operations: `mkdir`, `mv`, `cp`, and `rm`.
- Input/output redirection with `>`, `>>`, and pipes (`|`).
- Searching and replacing text with tools like `grep` and `sed`.
- Configuring a `.bash_profile` with custom aliases and prompts.
- Working with environment variables using `export`.

## Project Structure

The project file system consists of directories for continents, each containing `.txt` files for various languages. There is also a `todo` directory containing additional files to organize.

Final structure:
```
lingua-franca/
├── africa/
│   ├── afrihili.txt
│   ├── afrikaans.txt
├── asia/
│   ├── arabic.txt
│   ├── chinese.txt
│   ├── hebrew.txt
│   ├── hindi.txt
│   ├── japanese.txt
│   ├── korean.txt
│   ├── malay.txt
├── europe/
│   ├── english.txt
│   ├── french.txt
│   ├── german.txt
│   ├── italian.txt
│   ├── portuguese.txt
│   ├── russian.txt
│   ├── spanish.txt
├── northamerica/
│   ├── english.txt
│   ├── french.txt
│   ├── spanish.txt
├── southamerica/
│   ├── portuguese.txt
│   ├── spanish.txt
├── todo/
│   ├── asian_language_files.txt
│   ├── empty_files.txt
├── translations/  # Empty directory for potential future use.
├── world/
│   ├── esperanto.txt
```

## Task Groups

### 1. Navigating the File System
- Navigated through directories using `cd`.
- Listed files and directories with `ls`.
- Created a new directory and file.

### 2. Viewing and Changing the File System
- Moved misplaced files to correct locations with `mv`.
- Copied and removed files as needed using `cp` and `rm`.
- Worked with wildcard characters (`*`) to batch-process files.

### 3. Redirecting Input and Output
- Saved file lists and search results into text files using `>`.
- Combined commands with pipes (`|`) for advanced operations.
- Replaced incorrect text strings across multiple files using `sed`.

### 4. Configuring the Environment
- Customized the terminal with a `.bash_profile`:
  - Added greeting messages.
  - Created aliases for common commands.
  - Customized the CLI prompt.
- Listed environment variables with `env`.

## Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/Danial-Changez/Lingua-Franca-CLI-Tasks.git
   cd lingua-franca
   
2. Explore the file structure:

```bash
ls -R
```
3. View and run individual command tasks in the terminal.

4. To set up the `.bash_profile`:

- Open the file:
```bash
nano ~/.bash_profile
```
- Follow the instructions in Task Group 4 to replicate the environment setup.

## Conclusion

The Lingua Franca CLI Tasks project is a comprehensive showcase of essential command-line skills, useful for working efficiently with file systems, scripting, and environment customization.
