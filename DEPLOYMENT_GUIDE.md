# 🚀 Portfolio Deployment Guide

## ✅ Git Setup Complete!

Your portfolio is ready to upload to GitHub. Follow these simple steps:

---

## 📋 Step 1: Create GitHub Repository

1. Open browser and go to: **https://github.com/new**
2. Fill in details:
   - **Repository name:** `portfolio`
   - **Description:** "My Professional Portfolio Website - Full Stack Developer"
   - **Visibility:** ✅ Public
   - **DON'T** check: Initialize with README, .gitignore, or license
3. Click **"Create repository"** button

---

## 📤 Step 2: Push Code to GitHub

After creating the repository, run these commands in your terminal (PowerShell):

```powershell
# Add GitHub repository as remote
git remote add origin https://github.com/kundan0008000/portfolio.git

# Push your code to GitHub
git push -u origin main
```

### If it asks for authentication:

**Option A: Using GitHub Token (Recommended)**
1. Go to: https://github.com/settings/tokens
2. Click: **"Developer settings"** → **"Personal access tokens"** → **"Tokens (classic)"**
3. Click: **"Generate new token"** → **"Generate new token (classic)"**
4. Token name: `Portfolio Upload`
5. Expiration: `90 days`
6. Select scopes: ✅ **repo** (check all boxes under repo)
7. Click **"Generate token"**
8. **COPY THE TOKEN** (you won't see it again!)
9. Use this token as password when pushing code

**Option B: Using GitHub Desktop**
1. Download: https://desktop.github.com/
2. Install and login
3. Add repository: `d:\Downloads\portfolio_website-main\portfolio_website-main`
4. Publish to GitHub

---

## 🌐 Step 3: Enable GitHub Pages (Live Website)

1. Go to your repository: `https://github.com/kundan0008000/portfolio`
2. Click **"Settings"** tab (top right)
3. Scroll down and click **"Pages"** in left sidebar
4. Under **"Source"**:
   - Branch: Select **"main"**
   - Folder: Select **"/ (root)"**
5. Click **"Save"**
6. Wait 2-3 minutes for deployment

### Your live website will be at:
```
https://kundan0008000.github.io/portfolio/
```

---

## 🎯 Alternative: Quick Deploy Commands

If you want to do everything in one go, copy-paste these commands:

```powershell
# Navigate to project
cd "d:\Downloads\portfolio_website-main\portfolio_website-main"

# Add remote (only if not added yet)
git remote add origin https://github.com/kundan0008000/portfolio.git

# Push to GitHub
git push -u origin main
```

---

## 🔄 Future Updates

When you make changes to your portfolio:

```powershell
# Stage all changes
git add .

# Commit changes
git commit -m "Updated portfolio content"

# Push to GitHub
git push
```

The live website will auto-update in 1-2 minutes! 🎉

---

## ✨ What's Already Done:

✅ Git repository initialized  
✅ All files committed  
✅ Branch renamed to 'main'  
✅ Git user configured  
✅ README.md created with full documentation  
✅ Modern UI with animations  
✅ Responsive design  
✅ All your details added  

---

## 🆘 Troubleshooting

### Problem: "Permission denied" error
**Solution:** Use Personal Access Token as password (see Option A above)

### Problem: "Remote already exists"
**Solution:** Remove and re-add remote
```powershell
git remote remove origin
git remote add origin https://github.com/kundan0008000/portfolio.git
```

### Problem: GitHub Pages not working
**Solution:** 
1. Check if `index.html` is in root folder (it is ✅)
2. Wait 5 minutes for GitHub to deploy
3. Check Settings → Pages for errors

---

## 📞 Need Help?

- GitHub Docs: https://docs.github.com/en/pages
- Git Docs: https://git-scm.com/doc

---

## 🎊 Once Live, Share Your Portfolio:

Update your resume with:
```
Portfolio: https://kundan0008000.github.io/portfolio/
GitHub: https://github.com/kundan0008000/portfolio
```

Add to LinkedIn profile in:
- Featured section
- About section
- Projects section

---

**Good Luck! 🚀 Your professional portfolio is ready to shine! ✨**

Last Updated: January 13, 2026
