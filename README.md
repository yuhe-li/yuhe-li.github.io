# yuhe-li.github.io

Personal academic website for [Yuhe Li](https://yuhe-li.github.io).  
Built with plain HTML and CSS — no build system required.

---

## Setup

### 1. Create the GitHub repository

Create a new repository named exactly `yuhe-li.github.io` on GitHub.

### 2. Add these files

Clone the repository and add all files, or initialize locally and push:

```bash
git init
git add .
git commit -m "Create personal academic website"
git branch -M main
git remote add origin https://github.com/yuhe-li/yuhe-li.github.io.git
git push -u origin main
```

### 3. Add your CV PDF

Place your CV at:

```
assets/cv.pdf
```

The CV page will embed it in an `<iframe>` and provide a download link.

### 4. Enable GitHub Pages

1. Go to your repository on GitHub.
2. Click **Settings → Pages**.
3. Under **Source**, select **Deploy from a branch**.
4. Set branch to `main` and folder to `/ (root)`.
5. Click **Save**.

### 5. Visit your site

After a few minutes, your site will be live at:

```
https://yuhe-li.github.io/
```

---

## Placeholders to replace before publishing

Work through this checklist before your first push:

- [ ] **`[MY NAME]`** — already filled as "Yuhe Li" throughout, but double-check all pages.
- [ ] **`[MY EMAIL]`** — already filled as `yli2492@wisc.edu`. Update if it changes.
- [ ] **`[MY_GITHUB_USERNAME]`** — already set to `yuhe-li` in all links.
- [ ] **`[LINKEDIN_URL]`** — LinkedIn links are commented out in the nav. Uncomment and add your URL if you want them.
- [ ] **`assets/cv.pdf`** — add your actual CV PDF here. The CV page will not display until this file exists.

---

## File structure

```
yuhe-li.github.io/
├── index.html       — Home page
├── cv.html          — CV page with PDF embed
├── research.html    — Research projects
├── teaching.html    — Teaching experience
├── styles.css       — Shared stylesheet (all design lives here)
├── README.md        — This file
└── assets/
    └── cv.pdf       — Your CV (add this yourself)
```

## Updating content

All content is inline in the HTML files. To update a page:

1. Open the relevant `.html` file.
2. Edit the text directly.
3. Commit and push — GitHub Pages redeploys automatically within a minute or two.

To change the design (colors, fonts, spacing), edit `styles.css`. CSS variables at the top of the file control the color palette and max-width.
