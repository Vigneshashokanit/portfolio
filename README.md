# 🚀 Vignesh Asokan — Portfolio

A stunning, interactive personal portfolio website with **automatic GitHub Pages deployment**.

## ✨ Live Demo
Once deployed: `https://YOUR-GITHUB-USERNAME.github.io/vignesh-portfolio/`

---

## 📁 Files in this Folder

```
vignesh-portfolio/
├── index.html                  ← Your portfolio (edit this!)
├── Vignesh_Sr_Business_Analyst.pdf   ← Your resume PDF (replace with yours)
├── .github/
│   └── workflows/
│       └── deploy.yml          ← Auto-deployment magic ✨
└── README.md
```

---

## 🔧 STEP-BY-STEP SETUP (One Time Only)

### Step 1 — Create a GitHub Account
Go to [github.com](https://github.com) → Sign Up (free).

### Step 2 — Create a New Repository
1. Click the **"+"** button → **New repository**
2. Name it: `vignesh-portfolio`
3. Set to **Public**
4. Click **Create repository**

### Step 3 — Upload Your Files
#### Option A: Drag & Drop (easiest)
1. Open your new repo on GitHub
2. Click **"uploading an existing file"**
3. Drag ALL files from this folder (including the `.github` folder)
4. Click **Commit changes**

#### Option B: Using Git (recommended)
```bash
# In your terminal / command prompt:
git init
git add .
git commit -m "Initial portfolio upload"
git remote add origin https://github.com/YOUR-USERNAME/vignesh-portfolio.git
git branch -M main
git push -u origin main
```

### Step 4 — Enable GitHub Pages
1. Go to your repo → **Settings** tab
2. Click **Pages** in the left sidebar
3. Under **Source** → select **GitHub Actions**
4. Click **Save**

### Step 5 — Your site is LIVE! 🎉
Wait ~2 minutes, then visit:
`https://YOUR-GITHUB-USERNAME.github.io/vignesh-portfolio/`

---

## 🔄 HOW AUTO-DEPLOYMENT WORKS

Every time you **edit and save** any file in the repo:
```
You edit index.html on GitHub
       ↓
GitHub detects the change
       ↓
GitHub Actions automatically runs
       ↓
Your portfolio updates LIVE within ~2 minutes 🚀
```

**You NEVER need to manually deploy!**

---

## ✏️ HOW TO EDIT YOUR PORTFOLIO

### Edit directly on GitHub (easiest):
1. Go to your repo
2. Click on **`index.html`**
3. Click the **pencil icon** ✏️ (Edit this file)
4. Make your changes
5. Click **"Commit changes"**
6. Your portfolio updates automatically in ~2 minutes!

### What to edit in `index.html`:
| What you want to change | Where to find it in the file |
|---|---|
| Your name | Search for `Vignesh Asokan` |
| Phone number | Search for `8939672781` |
| Email | Search for `vigneshmech113@gmail.com` |
| LinkedIn URL | Search for `linkedin.com/in/vignesh` |
| Job titles / experience | Find the `exp-panel` sections |
| Skills & percentages | Find `data-w="95"` etc. |
| Certifications | Find `cert-list` section |
| Impact numbers | Find `data-count="40"` etc. |
| "Available for opportunities" | Find `hero-pre-badge` |

### Replace your resume PDF:
- Delete the old `Vignesh_Sr_Business_Analyst.pdf`
- Upload your new PDF with the **same filename**
- It auto-links throughout the site!

---

## 🎨 CUSTOMIZATION TIPS

### Change accent color (currently green `#63ebc2`):
In `index.html`, find:
```css
--accent: #63ebc2;
```
Replace with any color, e.g.:
- Blue: `#4da6ff`
- Gold: `#f5a623`
- Purple: `#9b5de5`
- Pink: `#e05c97`

### Change "Available for opportunities":
Find `hero-pre-badge` and change the text:
- `"Available for opportunities"` → `"Open to freelance"`
- `"Available for opportunities"` → `"Currently employed"`

---

## 🌐 SHARING YOUR PORTFOLIO

Your portfolio link will be:
```
https://YOUR-GITHUB-USERNAME.github.io/vignesh-portfolio/
```

Share this on:
- Your LinkedIn profile (Website field)
- Email signature
- Job applications
- Business cards

---

## ❓ TROUBLESHOOTING

**Site not updating?**
→ Go to your repo → **Actions** tab → check if the workflow ran successfully

**Deployment failed?**
→ Make sure **Settings → Pages → Source** is set to **GitHub Actions**

**Resume PDF not downloading?**
→ Make sure `Vignesh_Sr_Business_Analyst.pdf` is in the root of your repo

---

*Built with HTML, CSS, JavaScript — No frameworks needed, ultra-fast loading!*
