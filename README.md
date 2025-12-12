# Personal Portfolio Website

A modern, responsive personal portfolio website with Home, About, Contact Info, and Photos pages.

## Features

- 🎨 Modern gradient design with purple/pink theme
- 📱 Fully responsive layout
- 🚀 Fast and lightweight
- ✨ Smooth animations and transitions
- 📄 Four main pages: Home, About, Contact Info, and Photos

## Pages

- **Home** (`index.html`) - Landing page with introduction and call-to-action buttons
- **About** (`about.html`) - Personal information, skills, and education
- **Contact Info** (`contact.html`) - Contact details and contact form
- **Photos** (`photos.html`) - Photo gallery

## How to Deploy to GitHub Pages

Follow these steps to push your portfolio to GitHub and make it live:

### Step 1: Create a GitHub Account (if you don't have one)
1. Go to [github.com](https://github.com)
2. Sign up for a free account

### Step 2: Create a New Repository
1. Click the "+" icon in the top right corner
2. Select "New repository"
3. Name your repository (e.g., `portfolio` or `yourname-portfolio`)
4. Make it **Public** (required for free GitHub Pages)
5. **DO NOT** initialize with README, .gitignore, or license (we already have files)
6. Click "Create repository"

### Step 3: Initialize Git in Your Project Folder

Open your terminal/command prompt and navigate to your project folder:

```bash
cd C:\Users\rosal\OneDrive\Desktop\carmeljade
```

Initialize Git (if not already initialized):
```bash
git init
```

### Step 4: Add All Files to Git

```bash
git add .
```

This adds all your files (HTML, CSS, etc.) to Git.

### Step 5: Make Your First Commit

```bash
git commit -m "Initial commit: Portfolio website"
```

### Step 6: Connect to GitHub Repository

Replace `YOUR_USERNAME` and `YOUR_REPO_NAME` with your actual GitHub username and repository name:

```bash
git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
```

For example, if your username is `johndoe` and repo is `portfolio`:
```bash
git remote add origin https://github.com/johndoe/portfolio.git
```

### Step 7: Push to GitHub

```bash
git branch -M main
git push -u origin main
```

You'll be prompted to enter your GitHub username and password (or use a Personal Access Token).

### Step 8: Enable GitHub Pages

1. Go to your repository on GitHub
2. Click on **Settings** (top menu)
3. Scroll down to **Pages** (left sidebar)
4. Under **Source**, select **Deploy from a branch**
5. Select **main** branch and **/ (root)** folder
6. Click **Save**

### Step 9: Access Your Live Website

After a few minutes, your site will be live at:
```
https://YOUR_USERNAME.github.io/YOUR_REPO_NAME/
```

For example: `https://johndoe.github.io/portfolio/`

## Updating Your Portfolio

Whenever you make changes to your portfolio:

1. **Save your files**

2. **Add changes to Git:**
   ```bash
   git add .
   ```

3. **Commit changes:**
   ```bash
   git commit -m "Updated portfolio content"
   ```

4. **Push to GitHub:**
   ```bash
   git push
   ```

Your changes will be live on GitHub Pages within a few minutes!

## Customization

### Change "Your Name"
- Replace "Your Name" in all HTML files with your actual name
- Update the title tags in each HTML file

### Add Your Photo
- Replace the placeholder in `index.html` with an actual image:
  ```html
  <img src="your-photo.jpg" alt="Your Name" class="hero-image">
  ```

### Add Real Photos
- Add your photos to a folder (e.g., `images/`)
- Update `photos.html` to use actual images:
  ```html
  <img src="images/photo1.jpg" alt="Description">
  ```

### Update Contact Information
- Edit `contact.html` with your real email, phone, and social media links

### Customize Colors
- Edit `styles.css` and modify the CSS variables in the `:root` section

## Troubleshooting

**Problem:** Git push asks for password but it doesn't work
- **Solution:** Use a Personal Access Token instead of your password
  1. Go to GitHub → Settings → Developer settings → Personal access tokens → Tokens (classic)
  2. Generate new token with `repo` permissions
  3. Use the token as your password when pushing

**Problem:** Website shows 404 error
- **Solution:** Make sure your repository is Public and GitHub Pages is enabled in Settings

**Problem:** Changes don't appear on the live site
- **Solution:** Wait a few minutes for GitHub Pages to rebuild, or check the Actions tab in your repository

## Need Help?

- [GitHub Pages Documentation](https://docs.github.com/en/pages)
- [Git Basics](https://git-scm.com/book/en/v2/Getting-Started-Git-Basics)

---

Happy coding! 🚀

