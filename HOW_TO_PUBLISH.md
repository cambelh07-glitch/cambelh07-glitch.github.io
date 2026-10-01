# Publishing this site on GitHub Pages

1. Sign in to GitHub and create a new public repository named exactly `YOUR-GITHUB-USERNAME.github.io` (use your real username).
2. On the new repository's page, choose **Add file > Upload files**, drag in everything in this folder (index.html, the assets folder, and the projects folder), and commit.
3. Go to **Settings > Pages**. Under "Build and deployment," set the source to **Deploy from a branch**, choose the `main` branch and the `/ (root)` folder, and save.
4. After a minute or two, the site is live at `https://YOUR-GITHUB-USERNAME.github.io`.

## Before you publish

Search index.html and projects/nova-transit-access.html for these placeholders and replace them:

- `YOUR-SUBSTACK` with your Substack address
- `YOUR-GITHUB-USERNAME` with your GitHub username

## Editing later

- Text lives in `index.html` (home page) and `projects/nova-transit-access.html` (project page). Comments marked with `=====` show where each section starts.
- Colors and fonts are set at the top of `assets/style.css`.
- To change the site, edit a file on GitHub (open it and click the pencil icon) and commit. The live site updates within a few minutes.
