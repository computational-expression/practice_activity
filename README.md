# Python and Git Practice Activity

## Setup

After clicking the GitHub Classroom link and accepting the assignment:

1. **Clone your repository**:
   - Copy the repository URL from your GitHub page (Under `Code`, `SSH`)
   - Open VS Code
   - Open terminal in VS Code
   - Navigate to your course `activities` directory and clone, for example, if you are storing your course files in `Desktop/cs100/activities`:
   ```bash
   cd Desktop/cs100/activities    # or wherever you keep course files
   git clone [YOUR_REPOSITORY_URL]
   cd git_activity
   ```

2. **Open the project in VS Code**:

   Using VS Code menu: File → Open Folder → select your `git_activity` directory

   You can also type the command below in your terminal but it will open the directory in a new VS Code window'
   
   ```bash
   code .    # Opens current directory in VS Code
   ```
   
## Python Programming Practice

Now let's create and run Python programs in VS Code.

### Create Your First Python File

1. **Create a new Python file**:
   - In VS Code, right-click in the Explorer panel or Click on "File" in the menu
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
   - In VS Code terminal: `python3 hello_world.py`

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
   ```

2. **Add your new files**:
   ```bash
   git add hello_world.py
   ```
   
   Or add all files at once:
   ```bash
   git add .
   ```

3. **Commit your changes**:
   ```bash
   git commit -m "Add hello world program"
   ```

4. **Push to GitHub**:
   ```bash
   git push origin main
   ```

5. **Verify on GitHub**:
   - Go to your repository on GitHub's website
   - Refresh the page
   - You should see your new Python files

### Git Challenge
Practice the complete workflow:

1. Make a small change to one of your Python files (add a comment)
2. Use `git status` to see the change
3. Add and commit the change with a descriptive message
4. Push to GitHub
5. Check your repository online to confirm the update
