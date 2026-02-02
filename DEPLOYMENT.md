# 🚀 Deploy Your Portfolio to Netlify

## Method 1: Drag & Drop (Easiest - Recommended)

### Steps:
1. **Go to Netlify**
   - Visit: https://www.netlify.com/
   - Click "Sign up" (you can use GitHub, GitLab, or Email)

2. **Deploy Your Site**
   - After login, you'll see "Add new site" or "Deploy manually"
   - Click on "Deploy manually" or drag & drop area
   - **Drag the entire `portfolio` folder** from your Desktop into the deploy area
   - Netlify will automatically upload and deploy your site

3. **Your Site is Live!**
   - Netlify will give you a URL like: `https://random-name-123.netlify.app`
   - You can customize this URL in Site Settings

4. **Customize Your Domain (Optional)**
   - Go to Site Settings → Domain Management
   - Click "Options" → "Edit site name"
   - Change to something like: `haris-portfolio.netlify.app`

---

## Method 2: Using Git (For Version Control)

### Prerequisites:
- GitHub account
- Git installed on your Mac

### Steps:

1. **Initialize Git Repository**
   ```bash
   cd /Users/aqib/Desktop/portfolio
   git init
   git add .
   git commit -m "Initial portfolio commit"
   ```

2. **Create GitHub Repository**
   - Go to https://github.com/new
   - Repository name: `portfolio`
   - Keep it Public
   - Don't initialize with README
   - Click "Create repository"

3. **Push to GitHub**
   ```bash
   git remote add origin https://github.com/YOUR_USERNAME/portfolio.git
   git branch -M main
   git push -u origin main
   ```

4. **Connect to Netlify**
   - Go to Netlify Dashboard
   - Click "Add new site" → "Import an existing project"
   - Choose "GitHub"
   - Select your `portfolio` repository
   - Click "Deploy site"

---

## 📝 Important Notes:

### Files to Deploy:
Make sure these files are in your portfolio folder:
- ✅ `index.html`
- ✅ `style.css`
- ✅ `script.js`
- ✅ `images/` folder (with all your project images)

### Custom Domain (Optional):
If you have a custom domain:
1. Go to Site Settings → Domain Management
2. Click "Add custom domain"
3. Follow the DNS configuration steps

### SSL Certificate:
- Netlify automatically provides FREE SSL (HTTPS)
- Your site will be secure by default

---

## 🎯 Quick Checklist Before Deploy:

- [ ] All images are in the `images/` folder
- [ ] Avatar image is at `images/profile/avatar.png`
- [ ] Project images are in `images/projects/`
- [ ] All Figma links are correct
- [ ] Test the site locally (open `index.html` in browser)

---

## 🔄 Updating Your Site:

### Method 1 (Drag & Drop):
- Just drag the updated folder again to Netlify
- It will create a new deployment

### Method 2 (Git):
```bash
git add .
git commit -m "Update portfolio"
git push
```
- Netlify will automatically redeploy

---

## 🆘 Troubleshooting:

**Images not showing?**
- Check that image paths are correct
- Make sure images folder is uploaded

**Site not updating?**
- Clear browser cache (Cmd + Shift + R)
- Check Netlify deployment logs

**Need help?**
- Netlify Support: https://www.netlify.com/support/

---

## 📱 After Deployment:

1. **Test on mobile devices**
2. **Share your portfolio URL**
3. **Update your resume/CV with the link**
4. **Share on LinkedIn/social media**

Your portfolio URL will be: `https://your-site-name.netlify.app`

Good luck! 🚀
