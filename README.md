# xe-nsa

Static site repository.

## Local preview

Open `index.html` directly in your browser, or run a local server:

```bash
python3 -m http.server 8080
```

Then visit http://localhost:8080

## Initialize and publish with GitHub

If this repository is not connected to a remote yet:

```bash
git add .
git commit -m "chore: initialize static site repository"
git remote add origin <your-repo-url>
git push -u origin main
```

## Deploy as a live site (GitHub Pages)

1. Push this repo to GitHub.
2. In GitHub: Settings -> Pages.
3. Under "Build and deployment", choose:
   - Source: Deploy from a branch
   - Branch: `main`
   - Folder: `/ (root)`
4. Save and wait for deployment.

Your site URL will be shown in the Pages settings once published.
