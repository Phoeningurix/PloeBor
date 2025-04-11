# App Name: PloeBor

## Authors:
- Timofei Borisov – Matrikel: 580092


## Description:
[Your App Name] is a [short and clear description of what your app does, its purpose, or the problem it solves].


## Git usage:

To ensure smooth collaboration and clean version control, please follow these steps when working on the project:

### 1. Start from Master

Before starting any work:

```bash
git checkout master
git pull
```
### 2. Create a Feature Branch

Split your work into small tasks. Each task should have its own feature branch:

```bash
git checkout -b feature/<name-of-your-feature>
```

### 3. Make Changes

Work on your task. Use git add to stage your changes. Commit frequently with meaningful messages:

```bash
git add .
git commit -m "Add <your message here>"
```

### 4. Set Upstream and Push

If it’s your first time pushing the feature branch:

```bash
git push --set-upstream origin feature/<name-of-your-feature>
```

For subsequent pushes:

```bash
git push
```

### 5. Create a Pull Request

Go to GitHub.
Create a Pull Request (PR) from your feature/<name> branch into master.

### 6. Resolve Conflicts (if any)

If your PR has conflicts:

```bash
git checkout feature/<name-of-your-feature>
git fetch origin
git merge origin/master
# Resolve conflicts manually if prompted
git add .
git commit -m "Resolve merge conflicts"
git push
```

Then go back to GitHub and complete the merge.
⚠️ Important: Never push directly to master. Always work through feature branches and PRs.
