To create a new repository and push it to GitHub using the command line, follow these steps:

Create a README file: This initializes a README file with the repository name.

bash
Copy code
echo "# se-assignment-day-3-environment-setup-Martin484" >> README.md
Initialize a Git Repository: This command creates a new Git repository in your current directory.

bash
Copy code
git init
Add the README file to the Staging Area: This stages the README file for commit.

bash
Copy code
git add README.md
Commit the Changes: This creates the first commit with a message.

bash
Copy code
git commit -m "first commit"
Rename the Branch (if necessary): If the default branch is not named main, rename it.

bash
Copy code
git branch -M main
Add a Remote Repository: This sets the URL for the remote repository where your code will be pushed.

bash
Copy code
git remote add origin https://github.com/Powerlearnproject/se-assignment-day-3-environment-setup-Martin484.git
Push to the Remote Repository: This command pushes your local main branch to the remote repository and sets up tracking.

bash
Copy code
git push -u origin main
These steps will set up a new Git repository locally, connect it to a GitHub repository, and push your initial commit.
