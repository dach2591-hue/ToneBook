# 🚀 ToneBook Deployment Guide

This guide will help you deploy ToneBook to GitHub Pages in just a few minutes.

## Prerequisites

- A GitHub account (free)
- Basic familiarity with GitHub (optional - we'll walk you through it)

## Option 1: Quick Deploy (Recommended)

### Step 1: Create GitHub Repository

1. Go to [GitHub](https://github.com) and sign in
2. Click the **+** icon in the top right → **New repository**
3. Repository name: `ToneBook` (or any name you prefer)
4. Description: "Worship Leader & Musician App"
5. Set to **Public** (required for free GitHub Pages)
6. Click **Create repository**

### Step 2: Upload Files

1. On your new repository page, click **uploading an existing file**
2. Drag and drop or select `index.html`
3. Scroll down and click **Commit changes**

### Step 3: Enable GitHub Pages

1. Go to your repository's **Settings** tab
2. Scroll down to **Pages** in the left sidebar
3. Under "Source":
   - Branch: Select **main** (or **master**)
   - Folder: Select **/ (root)**
4. Click **Save**

### Step 4: Access Your App

Wait 1-2 minutes for GitHub to build your site, then visit:
```
https://yourusername.github.io/ToneBook/
```

Replace `yourusername` with your actual GitHub username.

🎉 **That's it!** Your ToneBook is now live and accessible from any device with a web browser.

---

## Option 2: Using Git (For Developers)

### Initial Setup

```bash
# Create a new directory
mkdir ToneBook
cd ToneBook

# Initialize git
git init

# Add your files
cp path/to/index.html .

# Create .gitignore
echo "# macOS
.DS_Store

# Windows
Thumbs.db

# Editor
.vscode/
.idea/" > .gitignore

# Commit files
git add .
git commit -m "Initial commit - ToneBook v11.3.2"

# Connect to GitHub (replace with your repo URL)
git remote add origin https://github.com/yourusername/ToneBook.git
git branch -M main
git push -u origin main
```

### Enable GitHub Pages

Follow **Step 3** from Option 1 above.

---

## Updating Your Deployment

### When You Have New Changes

1. Go to your repository on GitHub
2. Click on `index.html`
3. Click the pencil icon (Edit file)
4. Paste the new content
5. Scroll down and click **Commit changes**

GitHub will automatically rebuild and deploy your site in 1-2 minutes.

### Using Git

```bash
# Make your changes to index.html
# Then commit and push
git add index.html
git commit -m "Update to v11.3.2"
git push
```

---

## Custom Domain (Optional)

Want to use your own domain like `worship.yourchurch.org`?

1. Buy a domain from any registrar (GoDaddy, Namecheap, etc.)
2. In your repository Settings → Pages → Custom domain
3. Enter your domain and click **Save**
4. Add these DNS records at your domain registrar:

```
Type: CNAME
Name: worship (or whatever subdomain you want)
Value: yourusername.github.io
```

5. Wait for DNS to propagate (can take up to 48 hours)

---

## Troubleshooting

### My page shows a 404 error

- **Wait**: GitHub Pages can take 1-2 minutes to build
- **Check Settings**: Make sure GitHub Pages is enabled and source is set to `main` / `/ (root)`
- **Verify URL**: URL should be `https://yourusername.github.io/RepositoryName/`
- **Repository Name**: If your repo isn't named `ToneBook`, use the actual name in the URL

### My changes aren't showing up

- **Hard Refresh**: Press `Ctrl+Shift+R` (Windows) or `Cmd+Shift+R` (Mac)
- **Clear Cache**: Clear your browser cache
- **Wait**: Changes can take 1-2 minutes to deploy
- **Check Commit**: Make sure your changes were actually committed

### The app doesn't work

- **Browser Console**: Press `F12` and check the Console tab for errors
- **File Name**: Make sure the file is named exactly `index.html`
- **Repository**: Must be public (or you need a paid GitHub account)

### I can't see my data on other devices

This is normal! ToneBook stores data locally in each browser. To share data:
1. Export songs on original device
2. Import on new device

---

## Backup Strategy

### Automatic (Recommended)

Set up regular backups using the app's Export feature:

1. Weekly: Export All Songs
2. Before big services: Export your setlist folder
3. Store exports in:
   - Cloud storage (Google Drive, Dropbox)
   - Email them to yourself
   - Save to multiple devices

### Version Control (Advanced)

Keep your exports in your GitHub repository:

```bash
# Create an exports directory
mkdir exports

# Add your export files
cp *.tone exports/

# Commit
git add exports/
git commit -m "Backup: 2026-01-20"
git push
```

---

## Multiple Environments

Want to have a test version and a production version?

### Create Two Repositories

1. **Production**: `ToneBook` → `https://yourusername.github.io/ToneBook/`
2. **Development**: `ToneBook-dev` → `https://yourusername.github.io/ToneBook-dev/`

Test changes in dev before pushing to production!

---

## Security & Privacy

### Data Privacy

- All song data is stored locally in the browser
- Nothing is sent to any server
- GitHub only hosts the HTML file (no data)

### Backup Security

- Export files are plain JSON (text)
- Can be encrypted before storing if needed
- Never share your exports publicly if songs are copyrighted

---

## Performance Tips

### Page Load Speed

GitHub Pages is fast, but you can optimize:

1. **Use a CDN**: Already built-in (Tailwind CSS, React are from CDNs)
2. **Enable Caching**: Automatic with GitHub Pages
3. **Minimize File Size**: The single HTML file is already optimized

### Browser Performance

- **Chrome/Edge**: Best performance
- **Safari**: Excellent on iOS/macOS
- **Firefox**: Good performance
- **Mobile Browsers**: Optimized for mobile Safari and Chrome

---

## Support

### Community

- **GitHub Issues**: Report bugs or request features
- **Discussions**: Share tips and ask questions

### Documentation

- **README.md**: Overview and quick start
- **CHANGELOG.md**: Version history
- **USER-GUIDE-EN.pdf**: Complete English guide
- **USER-GUIDE-ES.pdf**: Guía completa en español

---

## Next Steps

1. ✅ Deploy to GitHub Pages
2. 📱 Bookmark on your devices
3. 🎵 Import your first songs
4. 📤 Export as backup
5. 🎸 Use in your next worship service!

---

**Deployment Time**: ~5 minutes  
**Cost**: Free  
**Maintenance**: Zero (GitHub handles everything)

🎉 **Enjoy your new ToneBook app!**
