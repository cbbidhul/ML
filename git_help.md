# ML

Basic git commands:
https://docs.github.com/en/github/importing-your-projects-to-github/adding-an-existing-project-to-github-using-the-command-line

1.  Initialize git repo -> One time
git init -b main 

2.  Add the files in your new local repository. This stages them for the first commit.  Adding folder, files to git - Staging the files, folders to commit
git add .
git add src
git add <filename>

3.  Commit the files that you've staged in your local repository.
git commit -m "First commit"

4. Push the changes in your local repository to GitHub.
git push origin main
