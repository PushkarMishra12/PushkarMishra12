# 🚀 Pushkar Mishra's GitHub Profile Setup Guide

Your profile repository is completely prepared at:
📁 **[`C:\Users\pushk\.gemini\antigravity-ide\scratch\github-profile\`](file:///C:/Users/pushk/.gemini/antigravity-ide/scratch/github-profile/)**

---

## 📁 What is Inside Your Repository
- **[`README.md`](file:///C:/Users/pushk/.gemini/antigravity-ide/scratch/github-profile/README.md)**: Configured with your username `PushkarMishra12`, your cropped avatar, full-stack & AI strengths, Orbit2Ore showcase, and live stats widgets.
- **[`assets/header-banner.svg`](file:///C:/Users/pushk/.gemini/antigravity-ide/scratch/github-profile/assets/header-banner.svg)**: Custom dark-mode SVG banner with your name and engineering titles.
- **[`assets/profile-avatar.png`](file:///C:/Users/pushk/.gemini/antigravity-ide/scratch/github-profile/assets/profile-avatar.png)**: Your cropped square profile headshot, perfectly framed for circular display.
- **[`assets/profile.png`](file:///C:/Users/pushk/.gemini/antigravity-ide/scratch/github-profile/assets/profile.png)**: Your original high-resolution photo.

---

## 🛠️ Step 1: Set Your Profile Avatar on GitHub
To make your profile picture appear on your main GitHub account icon:
1. Open **[github.com/settings/profile](https://github.com/settings/profile)**.
2. Click **Edit** on your profile picture.
3. Upload **[`assets/profile-avatar.png`](file:///C:/Users/pushk/.gemini/antigravity-ide/scratch/github-profile/assets/profile-avatar.png)** (or `assets/profile.png`) and click **Save**.

---

## 🛠️ Step 2: Fix Your Local Git Email Config
Run these commands in PowerShell so your commits count toward your GitHub contribution streak:
```powershell
git config --global user.name "Pushkar Mishra"
git config --global user.email "pushkarmishra.nea10@gmail.com"
```

---

## 🛠️ Step 3: Publish to GitHub

1. Go to **[github.com/new](https://github.com/new)**.
2. Set **Repository name** to: **`PushkarMishra12`**.
3. Set the repository to **Public**.
4. Leave "Add a README file" **unchecked**.
5. Click **Create repository**.

### Push Your Profile Files:
Open PowerShell and run:
```powershell
cd "C:\Users\pushk\.gemini\antigravity-ide\scratch\github-profile"

# Initialize git
git init
git add .
git commit -m "feat: launch personal engineering profile README"

# Link to your PushkarMishra12 repository and push
git branch -M main
git remote add origin https://github.com/PushkarMishra12/PushkarMishra12.git
git push -u origin main
```
