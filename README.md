GITHUB BASICS

1. Create a GitHub Repository
Go to https://github.com/new
Create a new repo — do not initialize with README if you're pushing existing files.

2. Open Terminal or Command Prompt
Navigate to the project folder:
cd path/to/your/project

3. Initialize Git (if not already initialized)
git init

4. Add Files to Git
git add .
Adds all files in the folder to staging. You can also add specific files like git add index.html.

5. Commit Your Changes
git commit -m "Initial commit"

6. Connect to GitHub Repository
Copy the repo URL from GitHub (HTTPS or SSH).
For HTTPS:
git remote add origin https://github.com/your-username/your-repo.git

7. Push Your Code to GitHub
If it's the first push:
git branch -M main
git push -u origin main
If your default branch is master, use that instead of main.

8. Next Time You Push Changes
After editing or adding files:
git add .
git commit -m "Your message"
git push

9. Check Git Status
To see changes before committing:
git status
