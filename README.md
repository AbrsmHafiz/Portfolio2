# Abrisam Hafiz — Engineering Portfolio

A clean, formal engineering portfolio website built for GitHub Pages.

## Structure

```
portfolio/
├── index.html              ← Landing page (all projects)
├── images/                 ← Project images
│   ├── image1.png
│   ├── image2.png
│   ├── image3.png
│   └── image4.png
└── projects/               ← Individual project pages
    ├── electric-bicycle.html
    ├── steam-turbine.html
    ├── mind-the-gap.html
    ├── robotic-hand.html
    ├── wind-turbine.html
    └── ftir-research.html
```

## How to Deploy on GitHub Pages

1. Create a new GitHub repository (e.g. `portfolio` or `yourname.github.io`)
2. Upload all files from this folder maintaining the folder structure
3. Go to **Settings → Pages**
4. Under **Source**, select `Deploy from a branch` → `main` → `/ (root)`
5. Click **Save** — your site will be live at `https://yourusername.github.io/portfolio/`

> If you name the repo `yourusername.github.io`, the site will be at `https://yourusername.github.io/` directly.

## Adding Your Own Images

To add real project photos, place image files in the `images/` folder and reference them in each project HTML file. For example, in `projects/electric-bicycle.html`, replace the placeholder `<div>` with:

```html
<img src="../images/your-photo.jpg" alt="Electric Bicycle Gearbox" style="width:100%; border-radius:4px; border:1px solid #e0e0e0; margin: 32px 0;">
```

For the landing page cards, replace the `<div class="project-card-img-placeholder">` block with:

```html
<img src="images/your-photo.jpg" alt="Project Name" class="project-card-img">
```
