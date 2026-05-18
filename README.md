# My Data Portfolio — Quarto + GitHub Pages

A professional CV portfolio for Data Engineering, Analytics Engineering, and BI roles.

## 🚀 Quick Start

```bash
# 1. Install Quarto: https://quarto.org/docs/get-started/
# 2. Clone this repo
git clone https://github.com/yourusername/cv-portfolio

# 3. Preview locally
cd cv-portfolio
quarto preview

# 4. Build
quarto render
```

## 📁 Structure

```
cv-portfolio/
├── index.qmd          # Home / About
├── resume.qmd         # Professional résumé
├── projects/          # Project pages
├── blog/              # Blog posts
├── contact.qmd        # Contact info
├── assets/            # CSS, images
├── _quarto.yml        # Site config
└── .github/workflows/ # Auto-deploy
```

## 🌐 Deploy

Push to `main` → GitHub Actions renders → publishes to GitHub Pages automatically.
Enable Pages in repo Settings → Pages → Source: GitHub Actions.
