# VinRobotics Talent — GitHub Pages Site

This repo hosts the website for **Physical Intelligence for Robotics** (VinRobotics Talent Program).

## 1) Create the repository
- Sign in to GitHub with the `vinrobotics-talent` account (or your org).
- Create a **public** repo named **`vinrobotics-talent.github.io`** (must match exactly).
- Upload all files from this ZIP to the repo **root** (index.html must live at the root).

## 2) Enable GitHub Pages
- Go to **Settings → Pages**.
- Under “Build and deployment”, choose **Deploy from a branch**.
- Select **Branch: `main`** and **Folder: `/ (root)`**.
- GitHub will publish your site at https://vinrobotics-talent.github.io

## 3) Swap the hero video (optional)
Edit the YouTube ID in the `<iframe>` `src` inside `<section id="hero-media">`:
```html
<iframe src="https://www.youtube.com/embed/6028Vm7cVcQ" ...></iframe>
```

## 4) Update the News links
Find the **News** section and replace `href="#"` with your article URLs.

## 5) Add mentor photos & links
- Replace placeholder headshots in `assets/img/mentors/` with 400×400 JPG/PNG files, using the same filenames.
- Update each mentor card (Website, Google Scholar, LinkedIn) with real links.

## 6) Edit copy
- All text is in `index.html` — Tracks, FAQ, Apply email, etc.
- No build step required (Tailwind via CDN; custom chips styled with plain CSS).

## 7) Optional: custom domain
If you have a domain, create a `CNAME` file at repo root with your domain and set DNS to GitHub Pages.

---

**Tip:** Commit with meaningful messages (e.g., `feat: add AI4VN 2025 news post`, `chore: update mentor photos`).

