# How to Contribute in a Quick and Easy Way

## Installation of Tools

1. [Git](https://git-scm.com/downloads) is essential, the first thing to download.
2. [Git LFS](https://git-lfs.com/) can be useful for uploading files with larger sizes.
3. [Github Desktop](https://desktop.github.com/) - I use it only for UI; I don't recommend using it for pushing or other actions.

## How to Use?

This will be a somewhat raw text, but I'll try to be as clear as possible.

I recommend installing the following extensions in VS Code:
- Prettier
- ESLint
- Prettier Code Formatter
- GitLens

### Example of a Pull Request (PR)

Let's say I want to add another page for an API Panel.

1. Open GitHub and select Danny's fork.
2. First, make sure that the main branch is clean with no commits and up to date.
3. 
   ![image](https://github.com/Berry-13/LibreChat/assets/81851188/4d627ee7-0f59-458f-8723-4f0eae447dd9)
   
4. Open "View all my branches" and create a new branch with a descriptive name for your task. For example: "ApiPanel."
5. In GitHub Desktop, select the branch you just created.

   ![image](https://github.com/Berry-13/LibreChat/assets/81851188/dd4374b8-419a-4406-97a3-999ba4118397)
   
6. Start modifying the code, and when you finish a part, commit the changes.

While testing the code, if you're working with the frontend, it might be frustrating to run `npm run frontend` and `npm run backend` every time. Instead, use `npm run frontend:dev` to see real-time changes on port 3090 (really!).

Example of commits:
- commit1: Created the frontend
- commit2: Fixed a bug in variable export
- commit3: Removed unnecessary comments and added translation support
- and so on...

### How?

- `git add *` adds all files to be committed.
- `git commit -m "name-of-your-commit"` creates a commit.
- `git push` uploads the changes.

Before doing all this, I recommend using GitHub Desktop to see what you've changed.
   ![image](https://github.com/Berry-13/LibreChat/assets/81851188/a04a7e81-7c75-4c77-8463-d35f603bedf7)

If `git commit` fails due to ESLint errors, read the error message and understand what's wrong. It could be an unused variable or other issues.

### Possible Various Problems

If you have the main branch with many commits and don't know what to do, follow this simple guide:

⚠️ Please do this only when you have no active PRs or when you're not working on the project. ⚠️

1. Go to GitHub and open "View all my branches"
2. Create a new branch, select Danny's repository as the source, and name it "clean"
3. Change the default branch to "clean"

![image](https://github.com/Berry-13/LibreChat/assets/81851188/0ac0f847-674c-4506-8fba-b02aaefa39f3)

![image](https://github.com/Berry-13/LibreChat/assets/81851188/d739610d-66c3-4d26-a1ea-ae1244af326a)

4. Delete the "main" branch and rename the "clean" branch to "main"
