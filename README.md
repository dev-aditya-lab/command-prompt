<h2 align="left">Hi 👋! My name is Aditya Kumar Gupra and I'm a student, from Jharkhand, India</h2>

###



<div align="left">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" height="30" alt="javascript logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg" height="30" alt="react logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" height="30" alt="html5 logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" height="30" alt="css3 logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nodejs/nodejs-original.svg" height="30" alt="nodejs logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/express/express-original.svg" height="30" alt="express logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mongodb/mongodb-original.svg" height="30" alt="mongodb logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/php/php-original.svg" height="30" alt="php logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/figma/figma-original.svg" height="30" alt="figma logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/canva/canva-original.svg" height="30" alt="canva logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/bootstrap/bootstrap-original.svg" height="30" alt="bootstrap logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/tailwindcss/tailwindcss-original-wordmark.svg" height="30" alt="tailwindcss logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" height="30" alt="git logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/github/github-original.svg" height="30" alt="github logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mysql/mysql-original.svg" height="30" alt="mysql logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nextjs/nextjs-original.svg" height="30" alt="nextjs logo"  />
</div>

###

<div align="left">
  <a href="https://www.youtube.com/channel/UCMKdocavstliQoOX7q0GHdg" target="_blank">
    <img src="https://img.shields.io/static/v1?message=Youtube&logo=youtube&label=&color=FF0000&logoColor=white&labelColor=&style=for-the-badge" height="35" alt="youtube logo"  />
  </a>
  <a href="https://www.instagram.com/_its._.aadi/" target="_blank">
    <img src="https://img.shields.io/static/v1?message=Instagram&logo=instagram&label=&color=E4405F&logoColor=white&labelColor=&style=for-the-badge" height="35" alt="instagram logo"  />
  </a>
  <a href="mailto:ad1123itya@gmail.com" target="_blank">
    <img src="https://img.shields.io/static/v1?message=Gmail&logo=gmail&label=&color=D14836&logoColor=white&labelColor=&style=for-the-badge" height="35" alt="gmail logo"  />
  </a>
  <a href="https://www.linkedin.com/in/its-aadi/" target="_blank">
    <img src="https://img.shields.io/static/v1?message=LinkedIn&logo=linkedin&label=&color=0077B5&logoColor=white&labelColor=&style=for-the-badge" height="35" alt="linkedin logo"  />
  </a>
</div>

---

# Command Prompt Documentation

Welcome to the comprehensive guide to using the Command Prompt! Whether you're a complete beginner or looking to master advanced commands, this documentation will walk you through everything you need to know about the Command Prompt in Windows.

## Table of Contents
1. [Introduction to Command Prompt](#introduction-to-command-prompt)
2. [Basic Commands](#basic-commands)
    1. [Navigating the File System](#navigating-the-file-system)
    2. [Managing Files and Folders](#managing-files-and-folders)
3. [Intermediate Commands](#intermediate-commands)
    1. [System Information and Diagnostics](#system-information-and-diagnostics)
    2. [Network Commands](#network-commands)
4. [Advanced Commands](#advanced-commands)
    1. [Batch Files and Scripting](#batch-files-and-scripting)
    2. [Task Scheduling and Automation](#task-scheduling-and-automation)
5. [Tips and Tricks](#tips-and-tricks)
6. [Resources](#resources)

---

## Introduction to Command Prompt

The Command Prompt, also known as CMD, is a command-line interpreter application available in most Windows operating systems. It's a powerful tool that allows users to execute commands to perform various tasks, ranging from basic file management to complex scripting.

### Opening the Command Prompt

To open the Command Prompt:
1. Press `Win + R` to open the Run dialog.
2. Type `cmd` and press `Enter`.

Alternatively, you can search for "cmd" or "Command Prompt" in the Start menu.

### Anatomy of the Command Prompt

When you open the Command Prompt, you'll see something like this:

```
C:\Users\YourUsername>
```

- `C:` indicates the current drive.
- `\Users\YourUsername` shows the current directory path.
- `>` is the prompt symbol, indicating the Command Prompt is ready to accept commands.

---

## Basic Commands

Let's start with some fundamental commands to get you comfortable with the Command Prompt.

### Navigating the File System

1. **`dir`**: Lists the files and directories in the current directory.
    ```shell
    dir
    ```

2. **`cd` (Change Directory)**: Changes the current directory.
    - To navigate to a different directory:
      ```shell
      cd path\to\directory
      ```
    - To go up one level in the directory structure:
      ```shell
      cd ..
      ```

3. **`cls`**: Clears the Command Prompt screen.
    ```shell
    cls
    ```

### Managing Files and Folders

1. **`mkdir` (Make Directory)**: Creates a new directory.
    ```shell
    mkdir NewFolder
    ```

2. **`rmdir` (Remove Directory)**: Deletes a directory.
    - To delete an empty directory:
      ```shell
      rmdir FolderName
      ```
    - To delete a directory and its contents:
      ```shell
      rmdir /s /q FolderName
      ```

3. **`copy`**: Copies files from one location to another.
    ```shell
    copy SourceFile Destination
    ```

4. **`move`**: Moves files from one location to another.
    ```shell
    move SourceFile Destination
    ```

5. **`del`**: Deletes one or more files.
    ```shell
    del FileName
    ```

---

## Intermediate Commands

### System Information and Diagnostics

1. **`systeminfo`**: Displays detailed configuration information about your computer.
    ```shell
    systeminfo
    ```

2. **`tasklist`**: Lists all currently running tasks and their details.
    ```shell
    tasklist
    ```

3. **`taskkill`**: Terminates a running process.
    ```shell
    taskkill /im ProcessName /f
    ```

### Network Commands

1. **`ipconfig`**: Displays the current network configuration.
    ```shell
    ipconfig
    ```

2. **`ping`**: Tests connectivity to another networked device.
    ```shell
    ping www.example.com
    ```

3. **`tracert`**: Traces the route taken to reach a networked device.
    ```shell
    tracert www.example.com
    ```

4. **`netstat`**: Displays active network connections and statistics.
    ```shell
    netstat
    ```

---

## Advanced Commands

### Batch Files and Scripting

Batch files are scripts that contain a series of commands to be executed sequentially by the Command Prompt.

1. **Creating a Batch File**:
    - Open Notepad.
    - Write your commands, one per line.
    - Save the file with a `.bat` extension (e.g., `script.bat`).

2. **Running a Batch File**:
    - In the Command Prompt, navigate to the directory containing the batch file.
    - Type the name of the batch file and press `Enter`.
      ```shell
      script.bat
      ```

### Task Scheduling and Automation

1. **`schtasks`**: Schedules commands and programs to run periodically or at a specific time.
    - To create a new scheduled task:
      ```shell
      schtasks /create /sc daily /tn "MyTask" /tr "C:\Path\To\Script.bat" /st 12:00
      ```
    - To list all scheduled tasks:
      ```shell
      schtasks /query
      ```

2. **`at`**: Schedules commands and programs to run on a computer at a specified time and date.
    ```shell
    at 14:00 /every:M,T,W,Th,F "C:\Path\To\Script.bat"
    ```

---

## Tips and Tricks

- **Autocomplete Paths**: Press `Tab` while typing a path to autocomplete folder and file names.
- **Command History**: Use the up and down arrow keys to cycle through previously entered commands.
- **Redirection Operators**: Use `>` to redirect output to a file and `>>` to append to a file.
  ```shell
  dir > filelist.txt
  ```

---

## Resources

- **Microsoft Documentation**: [Command-Line Reference](https://docs.microsoft.com/en-us/windows-server/administration/windows-commands/windows-commands)
- **SS64**: [Comprehensive Command List](https://ss64.com/nt/)
- **Stack Overflow**: [Community Support](https://stackoverflow.com/)

---

