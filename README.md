# Python and Git Practice Activity

## Setup

After clicking the GitHub Classroom link and accepting the assignment:

1. **Clone your repository**:
   - Copy the repository URL from your GitHub page (green `Code` button -> SSH)
   - Open VS Code
   - Navigate to your course `activities` directory and clone, for example, if you are storing your course files in `Desktop/cs100/activities`:
   ```bash
   cd Desktop/cs100/activities    # or wherever you keep course files
   git clone [YOUR_REPOSITORY_URL]
   cd git_activity
   ```

---
**If you don't have Git installed:**

* On Mac: Open Terminal and run:
   ```bash
   brew install git
   ```
   (If you don't have Homebrew, install it from https://brew.sh first.)

* On Windows: Download and install Git from https://git-scm.com/download/win

* On Linux: Open Terminal and run:
   ```bash
   sudo apt-get update
   sudo apt-get install git
   ```
---

2. **Open the project in VS Code**:

   Use VS Code menu: File → Open Folder → select your `git_activity` folder

## Python Programming Practice

Now let's create and run Python programs in VS Code.

### Create Your First Python File

1. **Create a new Python file**:
   - In VS Code, right-click in the Explorer panel or select `File` in the menu
   - Select "New File"
   - Name it `hello_world.py`

2. **Write your first program**:
   ```python
   #!/usr/bin/env python3
   """
   My first Python program for CMPSC 100
   Author: [Your Name]
   Date: September 2, 2025
   """

   def main():
       """Main function that demonstrates basic Python concepts."""
       
       # Basic output
       print("Hello, World!")

   if __name__ == "__main__":
       main()
   ```

3. **Run your Python program**:
   - In VS Code terminal: `python hello_world.py` or `python3 hello_world.py`

## Git Workflow Practice

### Configure Git (first time only)
If you haven't configured Git before:

```bash
git config --global user.name "Your Full Name"
git config --global user.email "your.email@allegheny.edu"
```

### Basic Git Workflow

1. **Check repository status**:
   ```bash
   git status
   # Shows which files have changed and what is staged for commit
   ```

2. **Add your new files**:
   ```bash
   git add hello_world.py
   # Stages the file so it will be included in the next commit
   ```
   
   Or add all files at once:
   ```bash
   git add .
   # Stages all changed files in the directory
   ```

3. **Commit your changes**:
   ```bash
   git commit -m "Add hello world program"
   # Saves a snapshot of staged changes with a message
   ```

4. **Push to GitHub**:
   ```bash
   git push origin main
   # Uploads your commits to the remote repository on GitHub
   ```

5. **Verify on GitHub**:
   - Go to your repository on GitHub
   - Refresh the page
   - You should see your new Python files

### 🎯 Git Challenge
Practice the complete workflow:


1. Make changes to your Python program:
   - Add a comment
   - Add a new variable (e.g., `my_number = 42`)
   - Add an expression (e.g., `result = my_number + 8`)
   - Add an assignment (e.g., assign a value to a variable)
2. Use `git status` to see the change
3. Add and commit the change with a descriptive message
4. Push to GitHub
5. Check your repository online to confirm the update
