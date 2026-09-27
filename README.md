# DemoRemo — Git and GitHub Practical

**Student Name:** Pranav Sudhir Yeola  
**Practical:** Git and GitHub — creating a local repository and pushing project files.

## Aim
To create a GitHub account, create a local Git repository, connect it to a remote
GitHub repository, and push project files using Git commands.

## Project files
- `index.html` — sample webpage containing the student's name and practical details.
- `README.md` — project information and Git commands.

## Git Bash procedure

Open Git Bash in this project folder and run:

```bash
git init
git config --global user.name "Pranav Sudhir Yeola"
git config --global user.email "YOUR-GITHUB-EMAIL"
git status
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/DemoRemo.git
git push -u origin main
```

Replace `YOUR-GITHUB-EMAIL` with the email configured for your GitHub/Git commits
and `YOUR-USERNAME` with your actual GitHub username. Create an empty GitHub
repository named `DemoRemo` before running the `git remote add` command.

## Updating the project

After editing a file, run:

```bash
git status
git add index.html
git commit -m "Modified index file"
git push
```
