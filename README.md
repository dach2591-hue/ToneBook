# 🎵 ToneBook v11.4.1

**The Ultimate Chord Transposer & Song Library for Worship Leaders**

ToneBook is a powerful, free, and easy-to-use web application designed for worship leaders, musicians, and bands. Manage your song library, transpose chords on the fly, and perform with confidence using our advanced Live Mode.

---

## 🌟 Key Features

### 📚 Song Management
- **Comprehensive Library**: Store unlimited songs with chords, lyrics, and metadata
- **Smart Organization**: 
  - Group by Artists
  - Create Custom Libraries (folders) for any purpose
  - Pin important songs for quick access
  - Search and filter instantly
- **Drag & Drop**: Easily move songs between folders
- **Import/Export**: Backup and share your entire library with `.tone` files

### 🎼 Music Tools
- **Chord Transposition**: Change key instantly with a single click
- **Nashville Number System**: Toggle between chord names and numbers
- **Capo Suggestions**: Automatic capo recommendations for guitarists
- **Metadata Tracking**: BPM, time signature, key, and custom notes

### 🎤 Performance Modes
- **Performance Mode**: 
  - Clean, distraction-free view for live use
  - Metronome with visual/audio options
  - Auto-scroll functionality
  - Large, readable text
  
- **Live Mode** (Auto-advance):
  - Automatic section progression based on BPM and time signature
  - Precise timing calculations
  - Visual progress indicators
  - Perfect for solo performances or practice

### 🎥 Media Integration
- **YouTube Embeds**: Practice with official videos
- **Audio Embeds**: Spotify, Apple Music support (audio-only for distraction-free practice)
- **Toggle Between**: Switch between video and audio seamlessly

### 🌙 Modern UI/UX
- **Dark Mode**: Easy on the eyes for late-night practice or dim stages
- **Responsive Design**: Works perfectly on phones, tablets, and desktops
- **Bilingual**: Full support for English and Spanish
- **Collapsible Sidebar**: Maximize screen space when needed

### 📤 Advanced Export
- **Web Share API**: Native sharing on mobile devices (AirDrop, WhatsApp, etc.)
- **Smart Export Options**:
  - Export entire library
  - Export by artist
  - Export by Custom Library
  - Export current song
  - Export with folder structure preserved

---

## 🆕 What's New in v11.4.1

### ✨ Improvements

#### 1. Larger Song Editor
- **Increased textarea height** from 384px to 600px
- See more of your song content while editing
- Better for songs with many verses
- Smaller font size for improved readability with more content visible

#### 2. Enhanced Custom Libraries Creation
- **New "+ button** in Custom Libraries header
  - Quick access to create new libraries
  - Click the + icon next to "Custom Libraries"
  - Consistent blue styling
  
- **Empty state handling**
  - Shows prominent "+ New Library" button when no libraries exist
  - Better onboarding for new users
  - Clear call-to-action

- **Bilingual prompts**
  - English: "Library name?"
  - Spanish: "¿Nombre de la biblioteca?"

#### 3. Streamlined Create Menu
- **Renamed** "Create Song" → "Create"
- Cleaner, more concise menu title
- Focuses on the core action

#### 4. Improved Help Documentation
- **Enhanced Custom Libraries section** in help modal
- **Step-by-step instructions** for creating libraries
- **Examples** in both English and Spanish
- **Better organization** of help content

### 🐛 Bug Fixes
- Fixed Custom Libraries section visibility
- Fixed language variable references
- Improved JSX structure
- Better error handling for library creation

---

## 🚀 Quick Start

### Option 1: Use Online (Recommended)
1. Visit the hosted version at your GitHub Pages URL
2. Start creating songs immediately - no installation needed!

### Option 2: Run Locally
1. Download `index.html`
2. Open it in any modern web browser (Chrome, Firefox, Safari, Edge)
3. That's it! Everything runs locally in your browser

### Option 3: Deploy Your Own
1. Fork this repository
2. Enable GitHub Pages in Settings
3. Your own ToneBook instance will be live!

---

## 📖 How to Use

### Creating Your First Song

1. Click **"+ New Song"** button in the Create menu
2. Fill in the song details:
   - **Title**: Song name
   - **Artist**: Original artist or composer
   - **Key**: Musical key (e.g., G, Am, Eb)
   - **BPM**: Tempo (beats per minute)
   - **Time Signature**: 4/4, 3/4, 6/8, etc.
   
3. Add lyrics and chords:
   ```
   [Intro]
   [C]    [G]
   
   [Verse 1]
   [C]Amazing [G]grace how [Am]sweet the [F]sound
   That [C]saved a [G]wretch like [C]me
   
   [Chorus]
   [F]  [C]       [G]
   How great thou art
   ```

4. (Optional) Add media:
   - YouTube video URL
   - Spotify/Apple Music embed

5. Click **"Save Song"**

### Creating Custom Libraries

Custom Libraries help you organize songs by occasion, setlist, or any category you want.

**To create a library:**
1. Look for **"Custom Libraries"** section in the sidebar
2. Click the **+ button** next to "Custom Libraries"
3. Enter a name (examples: "Sunday Service", "Christmas", "Youth Night")
4. Click OK

**To add songs to a library:**
- Click the 📁 icon on any song
- Select which library to add it to
- Or drag & drop songs into libraries (desktop)

**Ideas for libraries:**
- Weekly services ("Sunday Jan 26", "Wednesday Night")
- Special occasions ("Easter", "Christmas", "Mother's Day")
- Practice sessions ("Rehearsal", "New Songs")
- Events ("Youth Camp 2026", "Conference")

### Transposing Chords

1. Open any song
2. Use the **+ / -** buttons next to the key
3. Chords update instantly
4. **Nashville Numbers**: Toggle to see I, IV, V instead of chord names
5. **Capo Suggestions**: Shown automatically when transposing

### Performance Mode

1. Open a song
2. Click **"Performance Mode"**
3. Features available:
   - Clean, large text display
   - Metronome (visual/audio)
   - BPM adjustment
   - Auto-scroll
   - Current section highlighting

### Live Mode (Auto-Advance)

1. Open a song in Performance Mode
2. Toggle **"Live Mode"** ON
3. Set your BPM accurately
4. Click **Play** ▶️
5. Sections advance automatically based on timing

**Perfect for:**
- Solo practice with click tracks
- Timing your arrangements
- Hands-free practice sessions

---

## 💾 Data Storage

### How It Works
- All data stored in **browser localStorage**
- No account required
- No data sent to servers
- 100% privacy

### Backup Recommendations
1. **Regular Exports**: Export your library monthly
2. **Multiple Backups**: Save `.tone` files to:
   - Cloud storage (Google Drive, iCloud, Dropbox)
   - External drive
   - Email to yourself
3. **Before Browser Reset**: Always export before clearing browser data

---

## 🔧 Technical Details

### Browser Compatibility
- ✅ Chrome/Edge (recommended)
- ✅ Firefox
- ✅ Safari (iOS/macOS)
- ✅ Mobile browsers

### Technologies Used
- Pure HTML/CSS/JavaScript
- React (via CDN)
- Lucide Icons
- No build process required
- No dependencies to install

---

## 📱 Mobile Tips

### iOS
- **Add to Home Screen**: Install as a web app
- **Share**: Use AirDrop to send `.tone` files to bandmates
- **Dark Mode**: Syncs with system preference
- **Landscape**: Rotate for wider view

### Android
- **Install App**: Chrome will prompt to install as PWA
- **Share**: Send via WhatsApp, Gmail, Google Drive
- **Split Screen**: View ToneBook + YouTube simultaneously

---

## 🤝 Contributing

ToneBook is open source and welcomes contributions!

### How to Contribute
1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test thoroughly
5. Submit a pull request

---

**Created with ❤️ for worship leaders and musicians worldwide**

---

## 🐛 Known Issues

### Current Limitations
1. **YouTube in Local Files**: Some videos may not embed when running as `file://` (use web server or GitHub Pages)
2. **Browser Storage**: Clearing browser data deletes songs (always export backups!)
3. **No Cloud Sync**: Data is local only (cloud sync planned for future versions)

### Workarounds
- **YouTube Issues**: Use "Open in YouTube" link as fallback
- **Storage Concerns**: Regular exports to `.tone` files
- **Multiple Devices**: Import/export to sync manually

---

## 💬 Support & Feedback

### Get Help
- Read this README thoroughly
- Check the **"How to Use"** section in-app (ℹ️ icon)
- Review example songs provided

### Report Issues
- Open a GitHub issue
- Include:
  - Browser and version
  - Steps to reproduce
  - Expected vs actual behavior
  - Screenshots if applicable

---
## 🙏 Acknowledgments

**Built for:**
- Worship leaders who need reliable tools
- Musicians who want to stay organized
- Teams who value simplicity
- Churches of all sizes

---

#### Author

Daniel Chay Perea

**ToneBook v11.4.1** - Making worship preparation simple and powerful.

*Last Updated: January 22, 2026*
