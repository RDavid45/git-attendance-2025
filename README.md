# CSE Git Attendance 2025

Welcome to the CSE Club's attendance repository! This is a fun little way to get familiar with Git and GitHub while tracking attendance.

[If you're new to Git!](#table-of-contents)

## How to Mark Your Attendance

1. First, clone the repository to your local machine.
2. Find the folder named by the date of the meeting you're attending (e.g. `2025-09-08`).
3. Create a new file inside the folder named `<first>_<last>`
4. In the file, answer the Question of the Week listed in the folder's `README.md`.
5. TODO

## Table of Contents

- [If you're new to Git](#if-youre-new-to-git)
  - [Getting a terminal](#getting-a-terminal)
  - [Installing Git](#installing-git)
  - [Cloning the Repository](#cloning-the-repository)
  - [Authenticating with GitHub](#authenticating-with-github)
- [How to Mark Your Attendance](#how-to-mark-your-attendance)

## If you're new to Git

Follow these steps to setup and get the repository on your local machine. Note, there are no Linux instructions; if you're on Linux, you don't need to
follow this guide.

### Getting a terminal

- **macOS**: macOS has several terminal options. Using the default Terminal app is fine. Another popular option is [iTerm2](https://www.iterm2.com/).
- **Windows**: Windows has a built-in terminal called [Command Prompt](https://en.wikipedia.org/wiki/Cmd.exe). You can also use Git Bash, which is bundled with git.

### Installing Git

- **macOS**: You can install git with [Homebrew](https://brew.sh/) by running `brew install git`. Homebrew is the most popular package manager for macOS.
- **Windows**: Download and install [Git for Windows](https://git-scm.com/download/win).

### Cloning the Repository

To get a copy of this project on your machine, you can ["clone"](https://www.atlassian.com/git/tutorials/setting-up-a-repository/git-clone) it.

1. Click the green `<> Code` button on the repository page.
2. Copy the clone URL.

Copy the URL and run this command in your terminal to clone the repository through HTTP:
```bash
git clone https://github.com/alexyoung/git-attendance-2025.git
```
This will create a new directory called `git-attendance-2025` in the directory you ran the command in.

## Authenticating with GitHub

First, you'll need to [create a GitHub account](https://github.com/join).

Now you'll need to authenticate with GitHub.

### GitHub CLI (Simplest)

Install the [GitHub CLI](https://cli.github.com/)

Run the following command to authenticate with GitHub:

```bash
gh auth login
```

This will open a browser window where you can log in to GitHub.

### Other

See official [GitHub docs](https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/about-authentication-to-github#authenticating-with-the-command-line) for alternate authentication methods

