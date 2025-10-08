# How to Deploy Your Website to GitHub Pages

This folder contains your developer website with support pages, privacy policy, and terms of service.

## 📁 What's Included

```
website/
├── index.html                          (Homepage - your developer profile)
├── support.html                        (Support page with contact info)
├── qr-barcode-studio/
│   ├── privacy.html                    (Privacy Policy for QR app)
│   └── terms.html                      (Terms of Service for QR app)
└── README.md                           (This file)
```

## 🚀 Deploy to GitHub Pages (Free Hosting)

### Step 1: Create GitHub Account
1. Go to https://github.com
2. Click "Sign up"
3. Follow the registration process (use your real email)

### Step 2: Create a New Repository
1. Log into GitHub
2. Click the **"+"** icon (top right) → **"New repository"**
3. **Repository name:** `canva-apps` (or any name you like)
4. **Description:** "Developer website for my Canva apps"
5. ✅ Check **"Public"**
6. ✅ Check **"Add a README file"**
7. Click **"Create repository"**

### Step 3: Upload Your Website Files
1. In your new repository, click **"Add file"** → **"Upload files"**
2. Drag and drop ALL files from the `website` folder:
   - `index.html`
   - `support.html`
   - Create a folder called `qr-barcode-studio` and upload the privacy.html and terms.html inside it
3. At the bottom, add a commit message: "Initial website upload"
4. Click **"Commit changes"**

### Step 4: Enable GitHub Pages
1. In your repository, click **"Settings"** (tab at the top)
2. Scroll down to **"Pages"** (in the left sidebar under "Code and automation")
3. Under **"Source"**, select:
   - **Branch:** `main`
   - **Folder:** `/ (root)`
4. Click **"Save"**
5. Wait 1-2 minutes for deployment

### Step 5: Get Your URLs
Your website will be live at:
```
https://YOUR-USERNAME.github.io/canva-apps/
```

Replace `YOUR-USERNAME` with your actual GitHub username.

**Your URLs for Canva submission:**
- **Homepage:** `https://YOUR-USERNAME.github.io/canva-apps/`
- **Support:** `https://YOUR-USERNAME.github.io/canva-apps/support.html`
- **Privacy Policy:** `https://YOUR-USERNAME.github.io/canva-apps/qr-barcode-studio/privacy.html`
- **Terms of Service:** `https://YOUR-USERNAME.github.io/canva-apps/qr-barcode-studio/terms.html`

---

## 📝 Alternative: Use the GitHub Web Interface

If uploading folders is confusing, here's an easier way:

### Creating the folder structure directly on GitHub:

1. In your repository, click **"Add file"** → **"Create new file"**
2. In the filename box, type: `qr-barcode-studio/privacy.html`
   - This automatically creates the folder!
3. Paste the contents of `qr-barcode-studio/privacy.html`
4. Commit the file
5. Repeat for `qr-barcode-studio/terms.html`
6. Upload `index.html` and `support.html` to the root

---

## ✅ Testing Your Website

After deployment (wait 2-3 minutes), visit your URLs:
- Check that all pages load correctly
- Click all links to make sure they work
- Verify the support email link opens your email client

---

## 🔄 Updating Your Website Later

To make changes:
1. Go to your repository on GitHub
2. Click on the file you want to edit
3. Click the **pencil icon** (Edit)
4. Make your changes
5. Scroll down and click **"Commit changes"**
6. Changes will be live in 1-2 minutes

---

## 💡 Tips

- Your website is 100% free and will stay online forever (as long as your GitHub account exists)
- You can add more apps in the future by creating new folders like `your-next-app/`
- You can customize the colors and styles in the HTML files (look for the `<style>` sections)

---

## ❓ Need Help?

If you get stuck:
1. Take a screenshot of where you're stuck
2. Let me know and I'll guide you through it

Once deployed, copy your URLs and paste them into the Canva Developer Portal!
