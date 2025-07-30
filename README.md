# Gym-Git-Exercise-Solutions

This project contains the terminal Git commands used during practice.

## History of Commands Used

```bash
# Create and enter project directory
mkdir "Gym Git Exercise"
cd "Gym Git Exercise"/

# Initialize Git
git init

# Create files
echo Hello World! > index.html
echo style.css
echo script.js

# Set main branch
git branch -M main

# Stage and commit
git add .
git commit -m "initial commit"

# Add remote and push
git remote add origin https://github.com/ngenziwingenzi/Gym-Git-Exercise-Solutions.git
git push -u origin main

# Pull with rebase
git pull origin main --rebase

# Open in VS Code
code .

# Extra Git operations
git push -u origin main
git branch dev
git checkout dev
git checkout -b test
git checkout dev
git branch -d test
