<!-- VERSION CONTROL -->

# What is Version Control

- Version is a system that allows engineers to track and manage changes to a software code (source code) over time.
- It helps keep a history changes, enables collaboration and ensures integrity of the codebase

## Core concepts

### Snapshot of a project:

- Every time changes are committed, a snapsot of the current project state is saved (created)
- These snapshots allow engineers to view, compare or roll back to any previous version

### Collaboration:

- Multiple engineers can work on the same codebase without overwriting each other's change.
- Branching and merging enable simultaneously work on different features or bug fixes

### Change Tracking

- Version control records who made what changes, when, and why
- This is essential for debugging and accountability

## Benefits of using GIT

- Decentralized nature
- Performance
- Collaboration
- Support for Automation

## Git Basics

- Settin up GIT

  - Linux:

  ```
  sudo apt-get install git
  ```

  - Mac:

  ```
  brew install fit
  ```

  - Windows:

  ```
  https://git-scm.com
  ```

### Core Commands

- Initialize a repository

```
git init
```

- Check Repository status

```
git status
```

- Stage changes

```
git add <file_name>         # Stage a specific file
git add .                   # Stage all changes
```

- Commit changes

```
git commit -m 'Describe your changes'
```

- Push Changes

```
git push origin <branch_name>
```

### Collaborating with branches

- Create a branch

```
git branch <branch name>        # Creates a branch
git checkout -b <branch_name>   # Creates a branch and switches to that branch
```

- Switch to the branch

```
git checkout <branch_name>
```
