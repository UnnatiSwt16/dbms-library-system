# Step 1: Create a project folder
mkdir dbms-library-system
cd dbms-library-system

# Step 2: Initialize Git
git init

# Step 3: Add your files (e.g., main.py, README.md)
touch main.py
echo "# Library Management System in Python & SQL" > README.md

# Step 4: Stage & Commit
git add .
git commit -m "Initial commit - Library System"

# Step 5: Link GitHub Repo
git remote add origin https://github.com/your_username/dbms-library-system.git

# Step 6: Push to GitHub
git push -u origin main
