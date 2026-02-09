# Contributing to SERVD

Thank you for your interest in contributing to the SERVD project!  
This document outlines how team members should contribute to the repository to ensure smooth collaboration.

---

## 🛠 Project Overview

SERVD is a frontend web project built using:

- HTML  
- CSS  
- JavaScript  

Later phases of the project will introduce React.

---

## 🌿 Branching Strategy

We use the following branch structure:

- **main** – Stable production-ready code  
- **dev** – Integration branch for tested features  
- **feature branches** – Individual work branches for each task  

### Important Rules

- No one should push directly to `main`
- All changes must go through Pull Requests (PRs)
- Every feature must be developed on its own branch

---

## 👣 Contribution Workflow

Follow these steps to contribute:

1. Make sure your local repository is up to date:

   git checkout dev  
   git pull origin dev  

2. Create a new feature branch:

   git checkout -b feature/your-feature-name  

3. Make your changes in the codebase.

4. Stage and commit your changes:

   git add .  
   git commit -m "Description of changes"  

5. Push your branch to GitHub:

   git push -u origin feature/your-feature-name  

6. Open a Pull Request on GitHub from your feature branch into `dev`.

---

## ✅ Pull Request Guidelines

When creating a Pull Request:

- Use a clear title  
- Describe what you changed
- Reference any related issue  
- Ensure your code runs without errors  

All Pull Requests must be reviewed and approved before merging.

---

## 📁 File Organization

Follow this structure when adding new files:

- `index.html` – Main entry point  
- `/css` – Stylesheets  
- `/js` – JavaScript files  
- `/assets` – Images and other media  

Do not add unrelated files to the repository.

---

## 🧪 Code Quality

- Write clean and readable code  
- Use meaningful commit messages  
- Test your changes before pushing  
- Keep commits small and focused  

---

## 💬 Communication

If you are unsure about anything:

- Ask questions in the team group  
- Tag the project lead for clarification  
- Discuss major changes before implementing  

---

Thank you for contributing to SERVD! 🚀
