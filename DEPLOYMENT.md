# Quick Deployment Guide for Cafe 2 Concrete Website

## Option 1: Deploy to Vercel (RECOMMENDED - Fastest & Easiest)

### Step-by-Step:

1. **Create GitHub Repository**
   - Go to https://github.com/new
   - Name it: `cafe2concrete-website`
   - Make it Public or Private
   - Don't initialize with README (we already have one)
   - Click "Create repository"

2. **Upload Files to GitHub**
   - Download all files from this folder
   - On your new GitHub repo page, click "uploading an existing file"
   - Drag and drop all files (index.html, README.md, logo.png, etc.)
   - Click "Commit changes"

3. **Deploy to Vercel**
   - Go to https://vercel.com
   - Sign up/Login (use GitHub account for easier connection)
   - Click "Add New..." → "Project"
   - Import your GitHub repository
   - Click "Deploy"
   - Done! Your site is live in ~30 seconds

4. **Custom Domain (Optional)**
   - In Vercel dashboard, go to your project
   - Click "Settings" → "Domains"
   - Add your custom domain (e.g., cafe2concrete.com)
   - Follow the DNS instructions provided

**Your live URL will be**: `https://your-project-name.vercel.app`

---

## Option 2: Deploy to Netlify

### Step-by-Step:

1. Create GitHub repo (same as above)
2. Go to https://netlify.com
3. Click "Add new site" → "Import an existing project"
4. Choose GitHub and select your repository
5. Click "Deploy site"
6. Done!

**Your live URL will be**: `https://your-site-name.netlify.app`

---

## Option 3: GitHub Pages (Free)

### Step-by-Step:

1. Create GitHub repo (same as above)
2. Upload all files
3. Go to repository Settings
4. Scroll to "Pages" section
5. Under "Source", select "main" branch
6. Click "Save"
7. Your site will be live in a few minutes

**Your live URL will be**: `https://yourusername.github.io/cafe2concrete-website`

---

## Quick Commands (If using Git from command line)

```bash
# Navigate to the folder with your files
cd /path/to/your/files

# Initialize git repository
git init

# Add all files
git add .

# Commit files
git commit -m "Initial commit - Cafe 2 Concrete website"

# Connect to GitHub (replace with your repo URL)
git remote add origin https://github.com/yourusername/cafe2concrete-website.git

# Push to GitHub
git branch -M main
git push -u origin main
```

---

## Testing Locally

Before deploying, you can test the website locally:

1. Simply open `index.html` in your web browser
2. Or use a local server:
   - Python 3: `python -m http.server 8000`
   - Python 2: `python -m SimpleHTTPServer 8000`
   - Node.js: `npx serve`
   - Then visit: http://localhost:8000

---

## Need Help?

- **Vercel Support**: https://vercel.com/support
- **Netlify Support**: https://docs.netlify.com
- **GitHub Pages**: https://pages.github.com

---

## Sharing with Client

Once deployed, share this with your client:
1. **Live Website URL**: [Your Vercel/Netlify URL]
2. **GitHub Repository**: [Your GitHub repo URL]
3. Tell them: "The website is live and ready for review!"

You can also share the Vercel/Netlify dashboard access so they can see deployment logs and analytics.
