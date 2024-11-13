# GitHub Flow Hello World Tutorial

A beginner-friendly guide to understanding GitHub Flow through a practical Hello World example. This repository helps you learn the fundamentals of GitHub's pull request workflow using Visual Studio Code as the preferred editor.

## Overview

This repository is for practicing the GitHub Flow - the essential workflow used on GitHub for creating and reviewing code. Through this Hello World example, you'll learn the basic GitHub features that are used every day by developers worldwide.

## What You'll Learn

In this tutorial, you'll:
- Create and use a repository
- Start and manage a new branch
- Make changes to a file and push them to GitHub as commits
- Open and merge a pull request
- Use VS Code effectively with GitHub

## Prerequisites

Before starting, make sure you have:
- A GitHub account
- Visual Studio Code installed (our preferred editor)
- Git installed (if using VS Code integration)
- No coding experience required!

### Setting Up VS Code for GitHub

1. **Install VS Code**
   - Download from [Visual Studio Code website](https://code.visualstudio.com/)
   - Follow the installation instructions for your operating system

2. **Install Required Extensions**
   - Open VS Code
   - Go to Extensions (Ctrl+Shift+X or Cmd+Shift+X)
   - Install these recommended extensions:
     - "GitHub Pull Requests and Issues" by GitHub
     - "GitLens — Git supercharged" by GitKraken
     - "GitHub Repositories" by GitHub

3. **Configure GitHub Authentication**
   - Press Ctrl+Shift+P (Cmd+Shift+P on Mac) to open Command Palette
   - Type "GitHub: Sign in"
   - Follow the authentication prompts

4. **Clone the Repository in VS Code**
   - Press Ctrl+Shift+P (Cmd+Shift+P on Mac)
   - Type "Git: Clone"
   - Paste your repository URL
   - Select a local folder for the repository

## Step-by-Step Guide

### 1. Create a Repository

Your first step is creating the `hello-world` repository:
1. Click the '+' dropdown in the upper-right corner
2. Select "New repository"
3. Name it `hello-world`
4. Add a description: "This repository is for practicing the GitHub Flow"
5. Choose "Public" visibility
6. Select "Add a README file"
7. Click "Create repository"

### 2. Create a Branch

Branching lets you work on different versions of your repository at the same time:

**Through GitHub:**
1. Go to the Code tab
2. Click the dropdown that says "main"
3. Type `readme-edits` in the text box
4. Select "Create branch: readme-edits from main"

**Through VS Code:**
1. Click the branch icon in the bottom-left corner
2. Click "Create new branch"
3. Enter "readme-edits"
4. Select "main" as the source

### 3. Make and Commit Changes

**Through GitHub:**
1. Under the `readme-edits` branch, click the `README.md` file
2. Click the edit button (pencil icon)
3. Write something about yourself in the editor
4. Write a commit message describing your changes
5. Click "Commit changes"

**Through VS Code:**
1. Edit README.md in VS Code
2. Preview changes with Ctrl+Shift+V (Cmd+Shift+V on Mac)
3. Open Source Control tab (Ctrl+Shift+G or Cmd+Shift+G)
4. Enter commit message
5. Click checkmark or press Ctrl+Enter (Cmd+Enter)
6. Click "Sync Changes" to push to GitHub

### 4. Open a Pull Request

**Through GitHub:**
1. Click the "Pull requests" tab
2. Click "New pull request"
3. Select `readme-edits` branch to compare with `main`
4. Review your changes in the diffs
5. Click "Create pull request"
6. Add a title and description
7. Click "Create pull request"

**Through VS Code:**
1. Open GitHub Pull Requests tab
2. Click "Create Pull Request"
3. Select your branch
4. Add title and description
5. Click "Create"

### 5. Merge Your Pull Request

1. Click "Merge pull request" at the bottom
2. Click "Confirm merge"
3. Delete the `readme-edits` branch once merged
4. Check the Code tab to see your published changes

## VS Code Keyboard Shortcuts

Common shortcuts for this workflow:
- `Ctrl+Shift+G` (Mac: `Cmd+Shift+G`): Open Source Control
- `Ctrl+Shift+P` (Mac: `Cmd+Shift+P`): Command Palette
- `Ctrl+Shift+V` (Mac: `Cmd+Shift+V`): Preview Markdown
- `Ctrl+Enter` (Mac: `Cmd+Enter`): Commit changes
- `Alt+Left/Right`: Navigate back/forward
- `Ctrl+B`: Toggle sidebar
- `` Ctrl+` `` (Mac: `` Cmd+` ``): Open integrated terminal

## VS Code Tips for GitHub Flow

1. **Using the Integrated Terminal**
   - Run git commands directly
   - Multiple terminals for different tasks
   - Quick access to branch and commit information

2. **Source Control Features**
   - Stage changes by clicking + next to files
   - View diffs by clicking files
   - Undo changes with "Discard Changes" option
   - View file history with GitLens

3. **GitHub Integration**
   - Comment on PRs directly
   - Review PR changes in editor
   - Resolve conflicts with merge editor
   - See inline blame annotations

4. **Workspace Customization**
   - Use workspace settings for consistent team configuration
   - Create custom tasks for common operations
   - Set up project-specific snippets

## Visual Guide

Here's what happens in the branching process:
```
main branch: ──────────────────────
                     │
feature branch:      │──────────
                     │         │
                  create    merge
                  branch    back to main
```

## Common Terms

- **Repository**: A project's folder containing all files and version history
- **Branch**: A parallel version of your repository
- **Commit**: A saved change to your files
- **Pull Request**: Proposed changes to a repository
- **Merge**: Combining changes from one branch into another

## Next Steps

After completing this tutorial:
1. Check your GitHub profile to see your contribution graph
2. Try creating another branch and making different changes
3. Practice the workflow again with a new file
4. Explore the GitHub Skills "Introduction to GitHub" course
5. Customize your VS Code environment for better productivity

## Resources

### GitHub Resources
- [GitHub Flow Guide](https://docs.github.com/en/get-started/quickstart/github-flow)
- [GitHub Skills Courses](https://skills.github.com/)
- [Setting up your GitHub Profile](https://docs.github.com/en/account-and-profile/setting-up-and-managing-your-github-profile)

### VS Code Resources
- [VS Code Docs](https://code.visualstudio.com/docs)
- [VS Code GitHub Integration](https://code.visualstudio.com/docs/editor/github)
- [Working with GitHub in VS Code](https://code.visualstudio.com/docs/editor/github)
- [VS Code Tips and Tricks](https://code.visualstudio.com/docs/getstarted/tips-and-tricks)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
