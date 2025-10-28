# JangaVoice Demo - GitHub Pages Hosting Guide

## Quick Start

Your JangaVoice USSD demo is now ready to be hosted on GitHub Pages!

### Steps to Host on GitHub Pages:

1. **Create a GitHub Repository**
   - Go to [GitHub](https://github.com) and create a new repository
   - Name it something like `jangavoice-demo`
   - Make it public

2. **Upload the HTML File**
   - Upload `jangavoice-demo.html` to your repository
   - Rename it to `index.html` (GitHub Pages looks for this file by default)

3. **Enable GitHub Pages**
   - Go to your repository Settings
   - Scroll down to "Pages" section
   - Under "Source", select "Deploy from a branch"
   - Select the `main` branch and `/ (root)` folder
   - Click Save

4. **Access Your Demo**
   - Your demo will be available at: `https://[your-username].github.io/[repository-name]/`
   - It may take a few minutes for the site to go live

## Alternative: Using Git Commands

```bash
# Initialize git repository
git init

# Add the HTML file (rename to index.html first)
git add index.html

# Commit
git commit -m "Initial commit: JangaVoice USSD demo"

# Add remote repository
git remote add origin https://github.com/[your-username]/[repository-name].git

# Push to GitHub
git branch -M main
git push -u origin main
```

## Features

The demo includes:
- ✅ JangaVoice brand colors with gradients
- ✅ Interactive USSD phone mockup
- ✅ Full navigation flow
- ✅ Responsive design
- ✅ Works in all modern browsers

## Brand Colors Used

- **Primary Blue**: #0455A4 (Janga)
- **Magenta/Pink**: #CE224E (Voice)
- **Light Blue/Cyan**: #4CA8D5
- **Orange**: #F49D20

All colors are used in beautiful gradients throughout the interface!

## Testing Locally

Simply open `jangavoice-demo.html` in any web browser to test it locally before deploying.

---

**Note**: The file is completely standalone - no external dependencies required!