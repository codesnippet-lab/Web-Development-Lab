# Practical 2: Portfolio Repository with an Initial Commit

## Aim
To create a personal portfolio project, initialize a Git repository and save the first version using an initial commit.

## Theory
Git is a version control system used to track changes in files. GitHub is an online platform used to store and share Git repositories.

A commit is a saved snapshot of a project at a particular point in time.

## Procedure
1. Create a portfolio project folder.
2. Create HTML, CSS and JavaScript files.
3. Open the project folder in VS Code.
4. Initialize a Git repository.
5. Add project files to the staging area.
6. Create the initial commit.

## Terminal Commands

```bash
mkdir My-Portfolio
cd My-Portfolio
touch index.html
touch style.css
touch script.js
git init
git add .
git commit -m "Initial commit"
```

## Explanation of Commands

- `git init` – Initializes a Git repository.
- `git add .` – Adds files to the staging area.
- `git commit -m` – Saves changes with a commit message.
- `git status` – Checks repository status.
- `git log` – Displays commit history.

## Folder Structure

```text
P2/
├── practical.md
├── screenshots/
└── My-Portfolio/
    ├── index.html
    ├── style.css
    ├── script.js
    ├── navbar.html
    └── README.md
```

## Result
Successfully created a personal portfolio project, initialized Git and learned how to create an initial commit.