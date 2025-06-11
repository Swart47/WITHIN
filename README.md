#!/bin/bash

# Check if git is installed
if ! command -v git &> /dev/null
then
    echo "Git is not installed. Please install git first."
    exit
fi

# Initialize git repo
git init

# Add all files
git add .

# Commit files
git commit -m "Initial commit: full stack Instagram clone"

# Rename branch to main
git branch -M main

# Add remote origin
git remote add origin https://github.com/swart47/within-instagram-clone.git

# Push to GitHub
git push -u origin main

echo "Done! Check your repo at https://github.com/swart47/within-instagram-clone"