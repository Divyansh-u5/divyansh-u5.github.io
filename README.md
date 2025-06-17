# Personal Blog on GitHub Pages

This repository contains the code for my personal blog, powered by [Jekyll](https://jekyllrb.com/) and hosted on **GitHub Pages**.

## 🚀 Quick Start

1. **Write a post**
   - Add a Markdown file to the `_posts` folder.
   - Name it using the pattern `YYYY-MM-DD-title.md`.
   - At the top of the file, include front-matter, e.g.
     ```yaml
     ---
     layout: post
     title: "My Awesome Post"
     date: 2025-06-18 09:00:00 +0530
     categories: [life, thoughts]
     ---
     ```
   - Write your content below the front-matter in Markdown.

2. **Preview locally (optional)**
   ```bash
   bundle install       # Install dependencies the first time
   bundle exec jekyll serve --livereload
   ```
   Open `http://localhost:4000` in your browser.

3. **Deploy**
   - Commit and push to the `main` branch.
   - GitHub Pages will automatically build and publish the site at:
     `https://<your-username>.github.io` (or the custom domain you configure).

## 🛠️ Customization
- Edit `_config.yml` to change site-wide settings (title, description, theme, pagination).
- Choose a different Jekyll theme by setting `theme:` in `_config.yml`.
- Add pages (e.g., `about.md`) with front-matter `layout: page`.

## 📂 Folder Structure
```
.
├── _posts/         # Your Markdown blog posts live here
├── _config.yml     # Site configuration
├── index.md        # Home page that lists the posts
├── Gemfile         # Dependencies for local development
└── README.md       # You are here
```

Happy blogging! ✍️ 