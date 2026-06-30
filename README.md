# Pranit Khodke — Portfolio

Static one-page portfolio site (HTML/CSS, no build step needed).

## Run locally in VS Code
1. Open this folder in VS Code.
2. Install the "Live Server" extension (if not already installed).
3. Right-click `index.html` → "Open with Live Server".
   (Or just double-click `index.html` to open it directly in your browser.)

## Push to GitHub
```bash
git init
git add .
git commit -m "Initial portfolio commit"
git branch -M main
git remote add origin https://github.com/Pranit2024/portfolio.git
git push -u origin main
```

## Deploy on Vercel
1. Go to vercel.com → sign in with GitHub.
2. Add New → Project → Import the `portfolio` repo.
3. Framework Preset: "Other" (no build command needed).
4. Click Deploy.
