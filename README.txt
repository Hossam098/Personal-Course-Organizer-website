# Personal Course Organizer Website 

## Project Overview
This is a personal learning management web application developed as part of my **DevOps & Cloud Engineering Diploma**. The project focuses on building a functional front-end while applying professional **Source Control (Git/GitHub)** workflows as outlined in the "Intro to Source Control" curriculum.

## Tech Stack
* **Front-end:** HTML5, CSS3
* **Version Control:** Git, GitHub

## Git & DevOps Skills Applied (Based on Curriculum)
I have implemented several advanced Git concepts to manage this project's lifecycle:

### 1. Core Git Workflow Commands
In addition to the advanced techniques, I utilized the fundamental Git lifecycle to manage the project:
* `git init`: To initialize the local repository.
* `git remote add`: To link the local repository with the remote GitHub repository.
* `git add`: To stage changes for commits.
* `git commit`: To record snapshots of the project history.
* `git push`: To upload local changes to the master branch on GitHub.
* `git pull`: To fetch and integrate remote changes.

### 2. Repository Management & Workflow
* **Branching Strategy:** Followed the *GitHub Flow* by creating feature branches (`feature/`, `fix/`) to keep the `main` branch stable.
* **GitHub Pages:** Deployed the site live using GitHub Pages.

### 3. Advanced Git Commands
* **Stashing:** Used `git stash` to temporarily shelf uncommitted changes in `courses.html` while switching contexts for urgent fixes.
* **Cherry-picking:** Selectively applied a specific commit (Social Media links update) from an experimental branch to the `main` branch using `git cherry-pick`.
* **Tagging:** Created release tags (e.g., `v1.0`) to mark stable versions of the application.

### 4. Conflict Resolution & Undoing Changes
* **Merge Conflicts:** Manually resolved conflicts in `index.html` by analyzing the diff markers and choosing the correct integration path.
* **Undo Operations:**
    * `git restore`: Reverted accidental changes in the working directory.
    * `git commit --amend`: Updated commit messages for better documentation.
    * `git revert`: Safely undid public commits by creating an inverse commit.

---
**Organized by:** Hossam Gamil Deeb
