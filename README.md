# My personal website

An academic personal site built with Jekyll + GitHub Pages, with separate
Home / About Me / Research / Teaching pages.

## Edit your details
1. Open `_config.yml` and change your name, tagline, email, GitHub username, and CV path.
2. Replace `assets/images/profile.jpg` with your own photo (keep the same filename, or update it in `_config.yml`'s layout).
3. Replace `assets/files/CV.pdf` with your real CV.
4. Edit the text inside `index.html`, `about-me.html`, `research.html`, `teaching.html`.

## Put it online (free) with GitHub Pages
1. Create a GitHub account, then create a new repository named **exactly** `yourusername.github.io`
   (use your real GitHub username).
2. Upload every file and folder in this project into that repository
   (drag them into GitHub's "Add file → Upload files", or use `git` — see below).
3. Go to the repo's **Settings → Pages**. Under "Build and deployment",
   set Source to **Deploy from a branch**, branch **main**, folder **/(root)**. Save.
4. Wait ~1 minute. Your site is live at `https://yourusername.github.io`.

GitHub builds the Jekyll site automatically — you don't run anything yourself.

## If you prefer the command line
```bash
git init
git add .
git commit -m "my website"
git branch -M main
git remote add origin https://github.com/yourusername/yourusername.github.io.git
git push -u origin main
```
