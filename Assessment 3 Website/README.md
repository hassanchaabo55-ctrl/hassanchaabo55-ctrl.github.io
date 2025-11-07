# Bart Simpson Portfolio Template

This is a Bootstrap 5-based portfolio website (landing, resume, projects, contact) used for Assessment 3.

Contents
- `index.html`, `resume.html`, `projects.html`, `contact.html`
- `css/` (custom.css)
- `js/` (scripts)
- `img/` (images)

How to upload this project to GitHub (PowerShell)

1. Initialize repo and commit locally:

```powershell
cd "c:\Users\hassa\OneDrive\Desktop\Web design\Assessment 3\Assessment 3 Website"
git init
git add .
git commit -m "Initial commit: portfolio site"
```

2. Create a remote repository on GitHub:
- Option A (web): go to https://github.com/new, create a repo (e.g. `bart-portfolio`), then copy the remote URL.
- Option B (CLI): if you have GitHub CLI (`gh`) installed and authenticated:

```powershell
gh repo create YOUR_USERNAME/REPO_NAME --public --source=. --remote=origin --push
```

3. Or add remote and push manually (replace with your repo URL):

```powershell
git remote add origin https://github.com/YOUR_USERNAME/REPO_NAME.git
git branch -M main
git push -u origin main
```

Authentication
- For `git push` you can use:
  - HTTPS with username + password (deprecated) — use a Personal Access Token (PAT) instead when prompted.
  - `gh auth login` (recommended) to authenticate via browser.
  - SSH: set up SSH key and use `git@github.com:USER/REPO.git` as remote.

Publish with GitHub Pages (optional)
- In your GitHub repo settings -> Pages, set source to `main` branch and `/ (root)` to serve the site.

Notes
- Replace `YOUR_USERNAME` and `REPO_NAME` with your GitHub username and desired repo name.
- The project is on OneDrive; pushing from OneDrive works but be mindful of sync conflicts.
- If you want, I can run the commands here or walk you through authentication.
