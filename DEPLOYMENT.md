# How to Deploy Your Personal Website

## Option 1: GitHub Pages (Recommended - Free)

### Step 1: Create GitHub Repository
1. Go to [GitHub.com](https://github.com) and sign in
2. Click the "+" button in the top right and select "New repository"
3. Name it `akshat-chavan-patil` or `personal-website`
4. Make it **Public** (required for free GitHub Pages)
5. Don't initialize with README (we already have files)
6. Click "Create repository"

### Step 2: Push Your Code
```bash
# Add the GitHub repository as remote (replace YOUR_USERNAME with your GitHub username)
git remote add origin https://github.com/YOUR_USERNAME/akshat-chavan-patil.git

# Push your code to GitHub
git branch -M main
git push -u origin main
```

### Step 3: Enable GitHub Pages
1. Go to your repository on GitHub
2. Click "Settings" tab
3. Scroll down to "Pages" section (in the left sidebar)
4. Under "Source", select "Deploy from a branch"
5. Select "main" branch and "/ (root)" folder
6. Click "Save"
7. Your site will be available at: `https://YOUR_USERNAME.github.io/akshat-chavan-patil/`

## Option 2: Netlify (Free)

### Step 1: Upload to Netlify
1. Go to [Netlify.com](https://netlify.com) and sign up
2. Click "New site from Git" or drag your folder to the deploy area
3. If using Git: Connect your GitHub account and select your repository
4. If dragging: Just drag your entire `personal-website` folder
5. Click "Deploy site"

### Step 2: Custom Domain (Optional)
1. In your Netlify dashboard, go to "Domain settings"
2. Click "Add custom domain"
3. Enter your domain (if you have one)

## Option 3: Vercel (Free)

### Step 1: Deploy with Vercel
1. Go to [Vercel.com](https://vercel.com) and sign up
2. Click "New Project"
3. Import your GitHub repository
4. Click "Deploy"

## Update Your SEO Settings

After deploying, update these files with your actual domain:

1. **index.html**: Replace `yourdomain.com` with your actual domain
2. **robots.txt**: Update the sitemap URL
3. **sitemap.xml**: Update the URL

## Submit to Search Engines

1. **Google Search Console**: 
   - Go to [Google Search Console](https://search.google.com/search-console)
   - Add your domain
   - Submit your sitemap

2. **Bing Webmaster Tools**:
   - Go to [Bing Webmaster Tools](https://www.bing.com/webmasters)
   - Add your domain

## Quick Commands for GitHub Pages

If you choose GitHub Pages, run these commands:

```bash
# Replace YOUR_USERNAME with your actual GitHub username
git remote add origin https://github.com/YOUR_USERNAME/akshat-chavan-patil.git
git branch -M main
git push -u origin main
```

Then follow the GitHub Pages setup steps above.
