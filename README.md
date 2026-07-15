
# REAMDE

# Knowledge Base

Personal technical knowledge base.

The purpose of this repository is to organize and synthesize information on:

- R
- Python
- Positron
- Computing and programming
- Epidemiology and statistics
- Machine learning
- Neural networks and AI
- AI agents and related tools

## Project setup

### 1. Create the local project folder

Created the following folder:

knowledge_base/

### 2. Verify Git is installed

Powershell: git --version

### 3. Configure Git identity

git config --global user.name "YOUR_GITHUB_USERNAME"
git config --global user.email "YOUR_GITHUB_EMAIL"

Verifications:

git config --global user.name
git config --global user.email

### 4. Create a new Git repository on GitHub

### 5. Verify where Positron's terminal is located and initially Git locally

Powershell: pwd
Powershell: git init
Powershell: git status
Powershell: git add .
First commit: git commit -m "Initialize knowledge base"
Powershell: git status

### 6. Connect to GitHub

git branch -M main
git remote add origin https://github.com/Nhazkal/knowledge-base.git
git push -u origin main

### 7. Create all folders + index.qmd file with minimal info

Powershell: quarto preview

### 8. Commit again

git status
git add .
git commit -m "Create initial Quarto website structure"
git push

### 9. Set up GitHub Pages deployment

