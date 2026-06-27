# 🐳 Docker Dynamos — Docker Learning Hub

A multi-page static website built as a collaborative GitHub assignment, hosted via **GitHub Pages**. The site introduces beginners to Docker — what containers are, how they differ from virtual machines, and the core commands used to get started.

**Live site:** `https://praby07.github.io/Docker-Dynamos/`


---

## 👥 Team — Docker Dynamos

| Member | Role | File Owned |
|---|---|---|
| Prabha | Home page | `index.html` |
| Rohith | About page | `about.html` |
| Rohith | Contact page | `contact.html` |
| Prabha | Styling | `style.css` |

---

## 📄 Pages

- **`index.html`** — Landing page introducing Docker: hero section, core concepts (images vs. containers, why Docker matters), a container-vs-VM comparison table, a sample Dockerfile, and a command cheat-sheet.
- **`about.html`** — Information about the team and the project background.
- **`contact.html`** — Contact form and team member links.
- **`style.css`** — Shared stylesheet used by all pages (dockyard/shipping-manifest theme: steel blue, concrete, cargo orange, and dock yellow).

---

## 🛠️ Tech Stack

- HTML5
- CSS3 (no frameworks — custom design system)
- Hosted on GitHub Pages

---

## 🌳 Branching Workflow

Each team member worked on a separate feature branch and merged into `main` via pull requests:

```
main
 ├── feature/index-page
 ├── feature/about-page
 ├── feature/contact-page
 └── feature/styles
```

1. Clone the repo and create your branch:
   ```
   git checkout -b feature/your-page
   ```
2. Make changes, commit, and push:
   ```
   git add .
   git commit -m "Describe your change"
   git push origin feature/your-page
   ```
3. Open a Pull Request into `main` on GitHub.
4. Review, resolve any conflicts (especially in `style.css`), and merge.

---

## 🚀 Running Locally

No build step required — it's a static site.

1. Clone the repo:
   ```
   git clone https://github.com/praby07/Docker-Dynamos.git
   ```
2. Open `index.html` directly in your browser, or serve it locally:
   ```
   npx serve .
   ```

---

## 📦 GitHub Pages Setup

1. Go to **Settings → Pages** in the repository.
2. Set source to the `main` branch, root folder (`/`).
3. Save — the site will be live at `https://praby07.github.io/Docker-Dynamos/`.

---

## 📌 Project Status

✅ Initial structure complete
✅ Home page (index.html) built
✅ About page (about.html) complete
✅ Contact page (contact.html) complete
✅ Final review and merge into main complete
🚀 GitHub Pages Live Hosting Deployment active!

---

*Built by Team Docker Dynamos as part of a collaborative GitHub Pages assignment, 2026.*
