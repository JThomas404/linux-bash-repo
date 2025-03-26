# Linux Bash Reference

Welcome to my Linux Bash Reference project—a concise guide to mastering Linux terminal commands and Bash scripting. This repository focuses on practical skills and foundational knowledge for efficient system management.

## Key Skills and Topics
- Mastering essential Linux commands for file and directory management.
- Writing and debugging Bash scripts using variables, loops, and conditionals.
- Automating tasks to boost productivity in Linux environments.

## Repository Highlights
- **Hands-On Examples**: Real-world demonstrations of command-line tools and scripting.
- **Structured Learning Path**: Covers fundamentals, scripting techniques, and advanced tips for optimisation.

## Purpose of This Project
This project highlights my ability to learn and apply technical concepts, troubleshoot effectively, and adapt to Linux-based systems.

## Script: `newghrepo.sh`
The `newghrepo.sh` script automates the process of creating a new GitHub repository and pushing local files to it. It simplifies repository setup by combining Git initialisation, GitHub API integration, and remote configuration into a single script.

### Features:
- Creates a `README.md` file with the repository name.
- Initialises a local Git repository and makes the first commit.
- Uses the GitHub API to create a new repository on GitHub.
- Configures the remote repository and pushes the local files to GitHub.

### Usage:
1. Set your GitHub username and personal access token in the script:
    ```sh
    GITHUB_USER="YourGitHubUsername"
    GITHUB_TOKEN="YourPersonalAccessToken"