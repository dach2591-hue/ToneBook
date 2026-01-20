# ToneBook - Chord Transposition & Worship Leader App

**Version 11.0.2** | January 20, 2026

A comprehensive web-based application for worship leaders and musicians to organize songs by artist, transpose chords, and enhance live performance experiences.

![ToneBook](https://img.shields.io/badge/version-11.0.2-blue.svg)

---

## ✨ What's New in v11.0

### 🎨 Artist Organization
- **Artist Field**: Add artist name to each song
- **Auto-Folders**: Songs automatically organized by artist
- **Smart Migration**: Existing songs moved to "Unknown Artist"
- **Artist Display**: Shows in all views (main, performance, live)

### 📁 New Menu Structure
- **Collapsible Menu**: Expand/collapse sidebar on all devices
- **Organized Sections**: Create Song, Import/Export, Songs
- **Artist Folders**: Browse songs by artist
- **ToneBook Icon**: Distinctive icon in menu header

---

## 🚀 Quick Start

### Web Version (Easiest)

Visit: **https://YOUR-USERNAME.github.io/ToneBook/**

No installation required! Works in any modern browser.

---

## 🎸 Key Features

### Song Management
- 📝 Create and edit songs with chords and lyrics
- 🎤 **Artist field** - organize by artist/band
- 📌 Pin songs to create setlists
- 🔄 Import/Export songs (JSON format)
- 🎵 Support for chord notation `[Am]`, `[F]`, etc.

### Performance Mode
- 🎭 Clean, readable display for live performance
- 🔀 Real-time chord transposition
- 🎹 Three display modes: Chords, Lyrics Only, Numbers
- 📏 Adjustable font size (50%-200%)
- ⏱️ Built-in metronome
- 🎤 Artist name displayed

### Live Mode
- 🎬 Automatic section advancement
- ⏰ Duration calculation based on BPM
- 📊 Visual progress bar
- 🎵 Section-by-section display

### Mobile Responsive
- 📱 Works on iPhone, iPad, Android
- 👆 Touch-friendly controls
- ↕️ Arrow buttons for reordering

---

## 📦 Installation for GitHub Pages

1. Fork this repository
2. Go to Settings → Pages
3. Set source to **main branch** / **root**
4. Access at: `https://YOUR-USERNAME.github.io/ToneBook/`

---

## 🎵 Quick Guide

### Creating a Song with Artist

1. Click **"+ Create Song"** → **"New Song"**
2. Enter:
   - **Title**: Song name
   - **Artist**: Artist/band name (e.g., "Elevation Worship")
   - **Key**: e.g., C, G, Am
   - **BPM & Time Signature**: Optional
3. Add chords and lyrics:
   ```
   [Intro x2]
   [C] [G] [Am] [F]
   
   [Verse 1]
   [C]Amazing [G]grace how [Am]sweet the [F]sound
   ```
4. Click **"Save"**

### Organizing by Artist

Songs are automatically organized:
```
📁 All Songs (15)
📁 Elevation Worship (5)
📁 Hillsong United (4)
📁 Bethel Music (3)
📁 Unknown Artist (3)
```

---

## 🔄 Import/Export

### Export Your Songs
1. Expand **Import/Export** menu
2. Click **"Export All"**
3. JSON file downloads

### Import Songs
1. Expand **Import/Export** menu
2. Click **"Import Songs"**
3. Choose JSON file
4. Songs merge automatically

**Backup regularly!**

---

## 📱 Mobile Usage

### iPad/Tablet (Recommended)
- Best for live worship
- Landscape orientation
- Arrow buttons (↑↓) for reordering

### Phone
- Good for practice
- Touch-optimized controls

---

## 📝 Version History

### v11.0.2 (January 20, 2026)
- **New**: Artist field for all songs
- **New**: Automatic organization by artist
- **New**: Collapsible sidebar menu
- **New**: ToneBook icon in menu header
- **New**: Artist displayed in all views
- **Enhancement**: Improved menu structure

### v10.10.1 (January 19, 2026)
- **Fix**: iPad arrow buttons for reordering
- **Enhancement**: Better responsive design

---

## 💻 Technical Details

- **Frontend**: React (Babel standalone)
- **Styling**: Tailwind CSS
- **Storage**: Browser LocalStorage
- **Format**: Single-file HTML application

### Browser Support
- Chrome 90+
- Safari 14+
- Firefox 88+
- Edge 90+

---

## 📄 License

MIT License - Free for personal and worship use.

---

## 👤 Author

**Daniel Chay Perea**

---

**Happy Worship Leading!** 🎸🙏✨

---

**Last Updated**: January 20, 2026 | **Version**: 11.0.2
