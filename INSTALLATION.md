# ToneBook v10.8 - Installation Guide

## 📦 What's Included

- **index.html** - Web version (works on any device)
- **ToneBook-Mac-v10.8.app.zip** - Mac application
- **README.md** - Complete documentation
- **ToneBook-v10.8-Complete-Package.zip** - Everything in one file

---

## 🌐 Web Version (Recommended for Most Users)

### Installation

1. **Download** `index.html`
2. **Save** to a convenient location:
   - Desktop
   - Documents folder
   - Dropbox/iCloud for sync across devices
3. **Double-click** to open in your browser
4. **Bookmark** or **Add to Home Screen** for easy access

### Add to Home Screen (Mobile)

**iOS (iPhone/iPad):**
1. Open `index.html` in Safari
2. Tap the **Share** button (box with arrow)
3. Scroll down and tap **"Add to Home Screen"**
4. Name it "ToneBook"
5. Tap **"Add"**
6. Now it appears like a native app on your home screen!

**Android:**
1. Open `index.html` in Chrome
2. Tap the **three dots** menu
3. Tap **"Add to Home Screen"**
4. Name it "ToneBook"
5. Tap **"Add"**

---

## 🍎 Mac App Version

### Installation

1. **Download** `ToneBook-Mac-v10.8.app.zip`
2. **Extract** the zip file (double-click)
3. **Drag** `ToneBook.app` to your **Applications** folder
4. **First launch:**
   - Right-click `ToneBook.app`
   - Select **"Open"**
   - Click **"Open"** in the security dialog
   - (Only needed first time - macOS security check)
5. **Subsequent launches:**
   - Double-click `ToneBook.app` normally
   - Or launch from Spotlight (Cmd+Space, type "ToneBook")

### Troubleshooting Mac App

**"ToneBook.app is damaged and can't be opened"**

This is a Gatekeeper security message. Fix it:

```bash
# Open Terminal and run:
xattr -cr /Applications/ToneBook.app
```

Then try opening again.

**"ToneBook can't be opened because it is from an unidentified developer"**

1. Go to **System Preferences** → **Security & Privacy**
2. Click **"Open Anyway"** button
3. Or right-click app → **Open** (as mentioned above)

**Chrome not installed?**

The Mac app tries to use Chrome for the best experience. If Chrome isn't installed:
- The app will open in your default browser
- Or install Chrome: https://www.google.com/chrome/

---

## ☁️ Online Version

**No installation needed!**

Just visit: **https://dach2591-hue.github.io/ToneBook/**

**Pros:**
- ✅ No download required
- ✅ Always up-to-date
- ✅ Works on any device
- ✅ Easy to share with team

**Cons:**
- ❌ Requires internet connection
- ❌ Slower initial load

---

## 💾 Data & Storage

### Where Are Songs Saved?

**All versions (Web, Mac, Online):**
- Songs saved in **browser's localStorage**
- Data stays on your device
- No cloud storage or account needed
- Completely private

### Important Notes

1. **Data is browser-specific:**
   - Songs in Chrome stay in Chrome
   - Songs in Safari stay in Safari
   - Each browser has separate storage

2. **Data is device-specific:**
   - Songs on your phone stay on your phone
   - Songs on your computer stay on your computer
   - Use Export/Import to sync between devices

3. **Clearing browser data = losing songs:**
   - Export songs regularly as backup!
   - Don't clear browser data without exporting first
   - Private/Incognito mode won't save songs

### Backing Up Your Songs

**Recommended: Export regularly**

1. Click **"Export All Songs"** button
2. Save the `.tone` file to:
   - iCloud Drive / Google Drive
   - Dropbox
   - External hard drive
   - Email to yourself
3. Keep multiple backups in different locations

### Syncing Between Devices

**Manual sync via Export/Import:**

1. **On Device 1:**
   - Export All Songs
   - Save `.tone` file to cloud storage (Dropbox, etc.)

2. **On Device 2:**
   - Download `.tone` file
   - Click "Import Songs"
   - Select the `.tone` file
   - Songs will merge with existing library

---

## 🔧 Advanced Setup

### Using with Multiple Computers

**Option 1: Cloud Folder**
1. Save `index.html` to Dropbox/iCloud/Google Drive
2. Open from cloud folder on all computers
3. Songs save to each computer's browser
4. Export/Import to sync song libraries

**Option 2: USB Drive**
1. Copy `index.html` to USB drive
2. Open from USB drive
3. Songs save to computer's browser (not USB)
4. Good for guest computers

**Option 3: Host on GitHub Pages**
1. Create GitHub repository
2. Upload `index.html`
3. Enable GitHub Pages
4. Access via URL from anywhere
5. Share URL with worship team

### Custom Hosting

Upload `index.html` to:
- Your church website
- Personal web server
- Netlify / Vercel (free)
- Any web host

Just upload the single HTML file - it's completely self-contained!

---

## 📱 Device Recommendations

### Best Experience

**For Worship Leaders:**
- iPad (10-12 inch) in landscape
- 2-column view in Performance Mode
- Large enough for easy reading during service

**For Musicians:**
- Tablet or laptop
- Stand or mount for hands-free viewing
- External monitor/TV for larger display

**For Practice:**
- Phone works great
- Easy to carry
- Perfect for quick reference

### Screen Size Recommendations

- **Phone (≤6.5"):** 1-column view, font size 120-140%
- **Tablet (7-11"):** 1 or 2-column, font size 100-120%
- **Laptop (≥13"):** 2-column view, font size 100%
- **Desktop/Projector:** 2-column, font size 100-140%

---

## 🎵 First-Time Setup

### Quick Start (5 minutes)

1. **Open ToneBook** (web or Mac app)
2. **Click "+ New Song"**
3. **Enter a song:**
   ```
   Amazing Grace
   
   Verse 1
   G            D
   Amazing grace how sweet the sound
   Em           C
   That saved a wretch like me
   ```
4. **Set Key:** G
5. **Set BPM:** 80
6. **Save Song**
7. **Click "Performance"** to see it in action!

### Import Sample Songs

If you have existing songs in text format:
1. Copy the text (with chords above lyrics)
2. Click **"+ New Song"**
3. Paste into the content area
4. Clean up formatting if needed
5. Save

---

## 🆘 Getting Help

### Common Issues

**Songs not saving?**
- Check browser allows localStorage
- Don't use Private/Incognito mode
- Export songs as backup

**Mac app won't open?**
- Right-click → Open (first time)
- Run: `xattr -cr /Applications/ToneBook.app`
- Check Chrome is installed

**Mobile sidebar won't close?**
- Tap the X button in sidebar header
- Tap outside the sidebar
- Tap a song to select and close

**Font size not changing?**
- Clear browser cache
- Force refresh (Ctrl+Shift+R or Cmd+Shift+R)
- Check you're on v10.8

### Support

- **Documentation:** See README.md
- **GitHub:** https://github.com/dach2591-hue/ToneBook
- **Updates:** Check GitHub for new versions

---

## ✅ Installation Checklist

### Web Version
- [ ] Downloaded index.html
- [ ] Saved to accessible location
- [ ] Opened in browser successfully
- [ ] Created first song
- [ ] Tested Performance Mode
- [ ] Exported songs as backup

### Mac App
- [ ] Downloaded and extracted ToneBook.app
- [ ] Moved to Applications folder
- [ ] Opened app (right-click → Open first time)
- [ ] App launches successfully
- [ ] Created first song
- [ ] Exported songs as backup

### Mobile
- [ ] Opened in Safari/Chrome
- [ ] Added to Home Screen
- [ ] Tested hamburger menu
- [ ] Tested Performance Mode
- [ ] Tested font size adjustment
- [ ] Exported songs as backup

---

## 🎉 You're Ready!

**ToneBook v10.8 is installed and ready to use!**

Start adding your worship songs and enjoy leading with confidence. 🎸

Remember to:
- Export your songs regularly
- Test Performance/Live Mode before services
- Share with your worship team
- Have fun! 🎵

---

**Version:** 10.8 (Final)  
**Last Updated:** January 16, 2026  
**Installation Guide Version:** 1.0
