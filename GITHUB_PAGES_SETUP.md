# GitHub Pages Deployment Instructions

Follow these steps to get your Image Compressor live on GitHub Pages:

## Step 1: Create a GitHub Repository

1. Go to https://github.com and sign in (or create an account if you don't have one)
2. Click the **+** icon in the top right, then **New repository**
3. Repository settings:
   - **Name**: `image-compressor` (or any name you prefer)
   - **Description**: "Simple web-based image compression tool"
   - **Public** (must be public for free GitHub Pages)
   - ✅ Check "Add a README file"
4. Click **Create repository**

## Step 2: Upload Your Files

### Option A: Using GitHub Web Interface (Easiest)

1. In your new repository, click **Add file** → **Upload files**
2. Download the `index.html` file I created for you
3. Drag and drop `index.html` into the upload area
4. Scroll down and click **Commit changes**

### Option B: Using Git (If you're familiar with it)

```bash
git clone https://github.com/YOUR-USERNAME/image-compressor.git
cd image-compressor
# Copy the index.html file into this folder
git add index.html
git commit -m "Add image compressor app"
git push
```

## Step 3: Enable GitHub Pages

1. In your repository, click **Settings** (top menu)
2. Scroll down to **Pages** in the left sidebar
3. Under "Source":
   - Select **Deploy from a branch**
   - Branch: **main** (or **master**)
   - Folder: **/ (root)**
4. Click **Save**

## Step 4: Wait & Access Your Site

1. GitHub will take 1-2 minutes to build your site
2. Refresh the Settings → Pages page
3. You'll see: **"Your site is live at https://YOUR-USERNAME.github.io/image-compressor/"**
4. Click that link!

## Your Live URL

Once deployed, your image compressor will be live at:
```
https://YOUR-USERNAME.github.io/image-compressor/
```

Replace `YOUR-USERNAME` with your actual GitHub username.

## Tips

- Bookmark this URL on your iPhone for easy access
- Share it with friends - it works for anyone!
- To update the site later, just upload a new `index.html` file
- The site is 100% free to host on GitHub Pages

## Troubleshooting

**Site not loading?**
- Make sure the file is named exactly `index.html` (lowercase)
- Wait 2-3 minutes after enabling Pages
- Check that your repository is set to Public

**Need to update the app?**
- Upload the new `index.html` file
- It will automatically update within a few minutes

---

Need help? Let me know!
