# ToneBook - Chord Transposition & Worship Leader App

**Version 10.10** | January 19, 2026

A comprehensive web-based application for worship leaders and musicians to organize songs, transpose chords, and enhance live performance experiences.

![ToneBook](https://img.shields.io/badge/version-10.10-blue.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)

---

## ✨ Features

### Song Management
- 📝 Create and edit songs with chords and lyrics
- 📌 Pin songs to create setlists
- 🔄 Import/Export songs (JSON format)
- 🎵 Support for chord notation `[Am]`, `[F]`, etc.
- 🎼 Nashville Number System support

### Performance Mode
- 🎭 Clean, readable display for live performance
- 🔀 Real-time chord transposition
- 🎹 Three display modes: Chords, Lyrics Only, Numbers
- 📏 Adjustable font size (50%-200%)
- 📊 1 or 2 column layout
- ⏱️ Built-in metronome with visual beats
- 🎯 Auto-hide menu (5 seconds) with persistent info bar
- ⬅️➡️ Navigate between pinned songs without exiting

### Live Mode
- 🎬 Automatic section advancement
- ⏰ Duration calculation based on measures and BPM
- 📊 Visual progress bar
- 🎵 Section-by-section display
- 🎼 Integrated metronome
- 🎯 Full-screen mode when playing
- ⏮️▶️⏭️ Transport controls

### Mobile Responsive
- 📱 Works on iPhone, iPad, Android
- 🖥️ Desktop, tablet, and mobile optimized
- 👆 Touch-friendly controls
- ↕️ Mobile-specific song reordering

---

## 🚀 Quick Start

### Web Version (Easiest)

Visit: **https://dach2591-hue.github.io/ToneBook/**

No installation required! Works in any modern browser.

### Mac Desktop App

1. Download `ToneBook-Mac-v10.10.app.zip`
2. Extract and drag to Applications folder
3. Open (may need to approve in Security & Privacy settings)

---

## 📖 Documentation

- **[English User Manual](USER-MANUAL-ENGLISH.md)** - Complete guide in English
- **[Manual de Usuario Español](MANUAL-USUARIO-ESPAÑOL.md)** - Guía completa en español
- **[Installation Guide](INSTALLATION.md)** - Detailed installation instructions

---

## 🎸 Quick Guide

### Creating Your First Song

1. Click **"New Song"**
2. Enter title, key (e.g., C, Db), BPM, and time signature
3. Add chords and lyrics:
   ```
   [Intro x2]
   //8 measures
   [C] [G] [Am] [F]
   
   [Verse 1]
   [C]Amazing [G]grace how [Am]sweet the [F]sound
   ```
4. Click **"Save"**

### Creating a Setlist

1. Click 📍 next to each song you want
2. Songs appear at top in order
3. Reorder:
   - **Desktop**: Drag with ≡ handle
   - **Mobile**: Use ↑↓ arrows

### Performance Mode

1. Open a song
2. Click **"Performance"**
3. Menu auto-hides after 5 seconds
4. Info bar shows: Title, Key, Tempo, Time
5. Use **◀ Prev** / **Next ▶** to navigate songs

### Live Mode

1. Format song with sections and measure counts:
   ```
   [Intro]
   //8 measures
   ```
2. Enter Performance Mode
3. Click **"LIVE"** button
4. Press **▶ Play**
5. Sections auto-advance based on duration

---

## 🎵 Song Format

### Basic Structure

```
[Intro x2]
//16 measures
[C] [G] [Am] [F]

[Verse 1]
//8 measures
[C]Amazing [G]grace how [Am]sweet the [F]sound
[C]That saved a [G]wretch like [C]me

[Chorus]
//8 measures
[F]How great [C]is our [G]God
```

### Supported Sections

- Intro
- Verse / Verso
- Chorus / Coro
- Bridge / Puente
- Outro
- Pre-Chorus
- Instrumental
- Interlude
- Solo

---

## 💻 Technical Details

### Technologies Used

- **Frontend**: React (via Babel standalone)
- **Styling**: Tailwind CSS
- **Icons**: Lucide React
- **Storage**: Browser LocalStorage
- **Format**: Single-file HTML application

### Browser Support

- Chrome 90+
- Safari 14+
- Firefox 88+
- Edge 90+

### Storage

- All data stored locally in browser
- ~5-10 MB for 100 songs
- No server required
- Works offline after initial load

---

## 📦 Installation

### For GitHub Pages Deployment

1. Fork this repository
2. Enable GitHub Pages in Settings
3. Set source to main branch / root
4. Access at: `https://[your-username].github.io/ToneBook/`

### For Local Development

1. Clone the repository:
   ```bash
   git clone https://github.com/[your-username]/ToneBook.git
   ```

2. Open `index.html` in your browser

That's it! No build process required.

---

## 🔄 Import/Export

### Export Your Songs

1. Click hamburger menu (☰)
2. Select "Export Songs"
3. JSON file downloads with all songs

### Import Songs

1. Click hamburger menu (☰)
2. Select "Import Songs"
3. Choose JSON file
4. Songs merge with existing (duplicates skipped)

**Backup regularly!** Export before important services.

---

## 📱 Mobile Usage

### iPad/Tablet (Recommended)

- Best for live worship leading
- Landscape orientation recommended
- All features available
- Use tablet stand or holder

### Phone

- Good for practice and preparation
- Portrait or landscape
- Touch-optimized controls
- Smaller screen = less visible from distance

---

## 🎯 Best Practices

### For Worship Leaders

1. **Before Service**:
   - Create/update all songs
   - Pin songs in setlist order
   - Verify keys and BPM
   - Export backup

2. **During Service**:
   - Use Performance Mode
   - Navigate with Prev/Next buttons
   - Use Live Mode for complex songs
   - Keep iPad/tablet on stand

3. **After Service**:
   - Export updated songs
   - Note any improvements needed

### Song Entry Tips

- Use consistent section names: `[Verse 1]`, `[Chorus]`
- Always use brackets for chords: `[Am]` not `Am`
- Add measure counts for Live Mode: `//8 measures`
- Include BPM and time signature for accurate timing

---

## 🐛 Troubleshooting

### Songs Not Saving

- Check browser storage settings
- Don't use private/incognito mode
- Clear browser cache if needed

### Chords Not Transposing

- Ensure chords are in brackets: `[Am]`
- Check chord notation is correct

### Live Mode Not Working

- Verify section format: `[Intro]` or `[Verse 1]`
- Add measure counts: `//8 measures`

### Mac App Security Warning

- Right-click → Open
- Or: System Preferences → Security → Open Anyway

---

## 📝 Version History

### v10.10 (January 2026)
- **New**: Centered header bar in Performance Mode
- **New**: Improved metronome integration
- **Fix**: Header overlap in Performance Mode
- **Fix**: Mobile responsiveness improvements
- **Enhancement**: Better info display when menu hidden

### v10.9 (January 2026)
- **New**: Prev/Next navigation in Live Mode
- **Fix**: Db vs C# display consistency
- **New**: Mobile song reordering with arrow buttons
- **Fix**: Stay in Performance/Live Mode when navigating

### v10.8 (January 2026)
- **New**: Mobile sidebar close button
- **Fix**: Font controls on mobile
- **Fix**: Two-column layout balancing
- **Fix**: Live Mode controls on mobile

[See full version history in manuals]

---

## 🤝 Contributing

Suggestions and feedback welcome!

- Open an issue for bugs
- Submit feature requests
- Share your experience

---

## 📄 License

MIT License - Feel free to use for personal and worship purposes.

---

## 👤 Author

**Daniel Chay Perea**

---

## 🙏 Acknowledgments

Created for worship leaders and musicians to enhance live worship experiences.

---

## 📞 Support

- Check the [User Manual](USER-MANUAL-ENGLISH.md)
- Open an issue on GitHub

---

**Happy Worship Leading!** 🎸🙏✨

---

## 🔗 Links

- **Live Demo**: https://dach2591-hue.github.io/ToneBook/
- **User Manual (English)**: [USER-MANUAL-ENGLISH.md](USER-MANUAL-ENGLISH.md)
- **Manual de Usuario (Español)**: [MANUAL-USUARIO-ESPAÑOL.md](MANUAL-USUARIO-ESPAÑOL.md)
- **Installation Guide**: [INSTALLATION.md](INSTALLATION.md)

---

**Last Updated**: January 19, 2026 | **Version**: 10.10
