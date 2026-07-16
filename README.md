# Audio Productivity - Legal & Support Pages

This repository contains the static web pages (Privacy Policy, Terms of Use, Support, and Delete Account) for the **Audio Productivity** app. 

It is designed to be hosted for free via **GitHub Pages**.

## Setup Instructions

To publish this website on GitHub Pages:

1. **Create a new repository** on GitHub (e.g., `audioproductivity-pages`).
2. **Push these files** to the `main` branch of that repository.
   ```bash
   cd audioProductivity-pages
   git init
   git add .
   git commit -m "Initial commit of static pages"
   git branch -M main
   git remote add origin https://github.com/YOUR_USERNAME/audioproductivity-pages.git
   git push -u origin main
   ```
3. **Enable GitHub Pages**:
   - Go to your repository on GitHub.
   - Click on **Settings** > **Pages** (under the "Code and automation" section on the left sidebar).
   - Under **Build and deployment**, set the Source to **Deploy from a branch**.
   - Select the `main` branch and `/ (root)` folder, then click **Save**.
   - Within a few minutes, your site will be live at `https://YOUR_USERNAME.github.io/audioproductivity-pages/`.

## Customization

Before publishing, be sure to open the `.html` files in a text editor and replace the placeholder text:
- Replace `[eebrerheem]` with your actual name or company name.
- Replace `[eebrerheem@yahoo.com]` with your actual eebrerheem@yahoo.com address.

You can also replace the `images/logo.png` file with your own high-resolution app icon.
