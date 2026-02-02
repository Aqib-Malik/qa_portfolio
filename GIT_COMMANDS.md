# 📝 Git Commands Reference

## 🚀 Push Changes to GitHub

### Basic Push Commands (Use these every time you make changes):

```bash
# Step 1: Add all changed files
git add .

# Step 2: Commit with a message
git commit -m "Your commit message here"

# Step 3: Push to GitHub
git push
```

---

## 📋 Common Git Commands

### Check Status
```bash
# See what files have changed
git status
```

### View Commit History
```bash
# See recent commits
git log --oneline -5
```

### Undo Changes (Before Commit)
```bash
# Discard changes in a specific file
git checkout -- filename.html

# Discard all changes
git reset --hard
```

### Update from GitHub
```bash
# Pull latest changes from GitHub
git pull
```

---

## 🔄 Complete Workflow Example

```bash
# 1. Make changes to your files in VS Code or any editor

# 2. Check what changed
git status

# 3. Add all changes
git add .

# 4. Commit with descriptive message
git commit -m "Updated phone number in contact section"

# 5. Push to GitHub
git push
```

---

## 💡 Useful Commit Message Examples

```bash
git commit -m "Added new project to portfolio"
git commit -m "Updated profile picture"
git commit -m "Fixed responsive design issues"
git commit -m "Changed color scheme"
git commit -m "Updated contact information"
git commit -m "Added new skills section"
```

---

## 🆘 Troubleshooting

### If push is rejected:
```bash
# Pull first, then push
git pull
git push
```

### If you made a mistake in commit message:
```bash
# Change the last commit message
git commit --amend -m "New correct message"
git push --force
```

### View remote repository URL:
```bash
git remote -v
```

---

## ⚡ Quick Commands (Copy & Paste)

### For regular updates:
```bash
git add . && git commit -m "Updated portfolio" && git push
```

### For specific file:
```bash
git add index.html && git commit -m "Updated index.html" && git push
```

---

## 📌 Your Repository

**GitHub URL:** https://github.com/Aqib-Malik/qa_portfolio

**Clone Command (if needed on another computer):**
```bash
git clone https://github.com/Aqib-Malik/qa_portfolio.git
```

---

## 🎯 Best Practices

1. **Commit often** - Don't wait too long between commits
2. **Write clear messages** - Describe what you changed
3. **Pull before push** - If working from multiple devices
4. **Test locally first** - Make sure changes work before pushing

---

## 🔐 Configure Git (One-time setup)

```bash
# Set your name
git config --global user.name "Qasim Mahmood"

# Set your email
git config --global user.email "ha2221415@gmail.com"

# Check configuration
git config --list
```

---

**Happy Coding! 🚀**
