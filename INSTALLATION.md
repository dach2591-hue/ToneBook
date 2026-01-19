# ToneBook Installation Guide

Complete installation instructions for all platforms.

---

## 📦 Installation Options

ToneBook is available in three formats:

1. **Web Version** (Recommended) - No installation
2. **Mac Desktop App** - Standalone application
3. **Self-Hosted** - Host on your own server

---

## 🌐 Option 1: Web Version (Easiest)

### Access Online

Simply visit: **https://dach2591-hue.github.io/ToneBook/**

**Advantages**:
- ✅ No installation required
- ✅ Always up to date
- ✅ Works on any device with a browser
- ✅ Instant access

**Requirements**:
- Modern web browser (Chrome, Safari, Firefox, Edge)
- Internet connection for initial load
- Works offline after first visit

### Bookmark for Easy Access

**iOS/iPad**:
1. Open in Safari
2. Tap Share button
3. Select "Add to Home Screen"
4. Icon appears on home screen like an app

**Android**:
1. Open in Chrome
2. Tap menu (⋮)
3. Select "Add to Home screen"
4. Icon appears on home screen

**Desktop**:
- Bookmark the URL
- Or use browser's "Install App" option

---

## 🖥️ Option 2: Mac Desktop App

### Download

Get the latest version: `ToneBook-Mac-v10.10.app.zip`

### Installation Steps

1. **Download** the ZIP file

2. **Extract** the ZIP file:
   - Double-click `ToneBook-Mac-v10.10.app.zip`
   - Or right-click → Open With → Archive Utility

3. **Install**:
   - Drag `ToneBook.app` to your Applications folder
   - Optional: Drag to Dock for quick access

4. **Open**:
   - Double-click ToneBook in Applications
   - Or click icon in Dock

### First Launch (Security)

macOS may show a security warning because the app isn't from the App Store.

**Method 1: Right-Click Open**
1. Right-click (or Control+click) on ToneBook.app
2. Select "Open"
3. Click "Open" in the dialog
4. App will open normally from now on

**Method 2: System Preferences**
1. Try to open ToneBook normally
2. macOS shows "cannot be opened" message
3. Go to: System Preferences → Security & Privacy
4. Click "Open Anyway"
5. Click "Open" to confirm

**Method 3: Terminal Command** (Advanced)
```bash
xattr -cr /Applications/ToneBook.app
```

### System Requirements

- **macOS**: 10.13 (High Sierra) or later
- **Storage**: 50 MB free space
- **RAM**: 100 MB

### Updating

1. Download new version
2. Drag to Applications (replace old version)
3. Your data is stored separately (won't be lost)

---

## 🌍 Option 3: Self-Hosted

### For GitHub Pages

**Fork Repository**:
1. Go to: https://github.com/[original-repo]/ToneBook
2. Click "Fork" button
3. Wait for fork to complete

**Enable GitHub Pages**:
1. Go to your forked repo Settings
2. Navigate to "Pages" section
3. Under "Source", select:
   - Branch: `main`
   - Folder: `/ (root)`
4. Click "Save"
5. Wait 1-2 minutes
6. Access at: `https://[your-username].github.io/ToneBook/`

**Custom Domain** (Optional):
1. In Pages settings, add your domain
2. Create CNAME record pointing to: `[your-username].github.io`
3. Wait for DNS propagation

### For Own Server

**Requirements**:
- Web server (Apache, Nginx, etc.)
- No database needed
- No server-side processing needed

**Installation**:
1. Download `index.html`
2. Upload to your web server
3. Access via browser

**Example (Apache)**:
```bash
# Copy file
cp index.html /var/www/html/tonebook/

# Access at:
http://your-domain.com/tonebook/
```

### For Local Development

**No Build Required**:
1. Download or clone repository
2. Open `index.html` in browser
3. That's it!

```bash
# Clone
git clone https://github.com/[your-username]/ToneBook.git
cd ToneBook

# Open in browser (macOS)
open index.html

# Open in browser (Linux)
xdg-open index.html

# Open in browser (Windows)
start index.html
```

---

## 📱 Mobile Installation

### iOS/iPadOS

**Add to Home Screen**:
1. Open https://dach2591-hue.github.io/ToneBook/ in Safari
2. Tap Share button (box with arrow)
3. Scroll down and tap "Add to Home Screen"
4. Name it "ToneBook"
5. Tap "Add"

**Result**: Icon on home screen, opens like native app

**Features**:
- Full-screen mode
- No browser UI
- Faster access
- Works offline after first visit

### Android

**Add to Home Screen**:
1. Open URL in Chrome
2. Tap menu (⋮) in top-right
3. Tap "Add to Home screen"
4. Name it "ToneBook"
5. Tap "Add"

**Result**: Icon on home screen

---

## 💾 Data Storage

### Where Is Data Stored?

**Web Version**:
- Browser's LocalStorage
- Specific to browser and domain
- Persists between sessions
- Not synced across devices

**Mac App**:
- Application's LocalStorage
- Stored in: `~/Library/Application Support/ToneBook/`
- Persists even if app is reinstalled

### Backup Your Data

**Important**: Always backup!

1. **Export Songs**:
   - Open ToneBook
   - Click menu (☰)
   - Select "Export Songs"
   - Save JSON file

2. **Save Export File**:
   - Cloud storage (Google Drive, Dropbox)
   - Multiple locations
   - Regular backups (weekly recommended)

3. **Restore**:
   - Open ToneBook
   - Click menu (☰)
   - Select "Import Songs"
   - Choose JSON file

---

## 🔄 Updating

### Web Version

- **Automatic**: Always latest version
- **Manual**: Clear browser cache to force update

### Mac App

1. Download new version
2. Replace old app in Applications
3. Your data is preserved

### Check Version

Look at bottom of main page or in About section.

Current version: **10.10**

---

## 🐛 Troubleshooting Installation

### Web Version

**"Page Not Loading"**:
- Check internet connection
- Try different browser
- Clear browser cache
- Disable browser extensions

**"Storage Full" Error**:
- Clear browser data
- Free up storage space
- Export songs first!

### Mac App

**"App is damaged and can't be opened"**:
- See [First Launch (Security)](#first-launch-security) above
- Most common issue with Mac app

**"App won't open"**:
- Check macOS version (need 10.13+)
- Try right-click → Open
- Check Security & Privacy settings

**"App crashes on launch"**:
- Delete app preferences:
  ```bash
  rm -rf ~/Library/Application\ Support/ToneBook/
  ```
- Reinstall app

### Data Issues

**"Songs disappeared"**:
- Check if using different browser/device
- Check if browser data was cleared
- Restore from backup export

**"Can't import songs"**:
- Verify JSON file is valid
- Check file isn't corrupted
- Try exporting and re-importing

---

## 🔒 Security & Privacy

### Data Privacy

- **All data stored locally** on your device
- **No cloud sync** (your data never leaves your device)
- **No tracking** or analytics
- **No account required**

### Permissions

**Web Version**:
- LocalStorage (for saving songs)
- Audio (for metronome)

**Mac App**:
- Same as web version
- No additional permissions needed

---

## 🌐 Browser Compatibility

### Recommended Browsers

| Browser | Version | Rating |
|---------|---------|--------|
| Chrome | 90+ | ⭐⭐⭐⭐⭐ Best |
| Safari | 14+ | ⭐⭐⭐⭐⭐ Best |
| Edge | 90+ | ⭐⭐⭐⭐⭐ Best |
| Firefox | 88+ | ⭐⭐⭐⭐ Good |

### Mobile Browsers

| Browser | Platform | Rating |
|---------|----------|--------|
| Safari | iOS/iPad | ⭐⭐⭐⭐⭐ Best |
| Chrome | Android | ⭐⭐⭐⭐⭐ Best |
| Chrome | iOS | ⭐⭐⭐⭐ Good |

---

## 💡 Tips

### Best Setup for Worship Leading

1. **iPad/Tablet** (Recommended):
   - Large screen
   - Portable
   - Touch controls
   - Add to home screen for app-like experience

2. **Desktop/Laptop**:
   - Largest screen
   - Full keyboard
   - Use Mac app or web version

3. **Phone**:
   - Backup device
   - Practice mode
   - Emergency use

### Recommended Accessories

- **iPad Stand**: For hands-free viewing
- **Bluetooth Page Turner**: For advancing songs
- **External Speaker**: For metronome in noisy environments

---

## 📞 Support

Need help with installation?

- Check [Troubleshooting](#troubleshooting-installation)
- Read [User Manual](USER-MANUAL-ENGLISH.md)
- Open GitHub issue

---

## ✅ Post-Installation

After installing, see:
- **[User Manual (English)](USER-MANUAL-ENGLISH.md)** - Complete guide
- **[Manual de Usuario (Español)](MANUAL-USUARIO-ESPAÑOL.md)** - Guía en español

---

**Installation Complete!** 🎉

Ready to start using ToneBook for worship leading! 🎸🙏
