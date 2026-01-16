# ToneBook - Worship Leader's Song Management App

**Version:** 10.8 (Final)  
**Live Demo:** https://dach2591-hue.github.io/ToneBook/

A comprehensive web-based application for worship leaders and musicians to manage songs, transpose chords, and perform live with confidence.

---

## ✨ Features

### 📚 Song Management
- **Create and edit songs** with chord notation
- **Organize with folders** - Add songs to multiple folders simultaneously
- **Search functionality** - Quickly find songs by title
- **Pin important songs** - Keep frequently used songs at the top
- **Import/Export** - Share song libraries with your team (.tone format)
- **Smart import** - Paste chord text from any website

### 🎵 Chord Transposition
- **Transpose to any key** - Up or down by semitones
- **Nashville Number System** - Toggle between chords and numbers (1-7 system)
- **Original key tracking** - Always know the original key
- **Automatic chord detection** - Recognizes common chord formats

### 🎭 Performance Mode
- **Clean full-screen view** - Distraction-free display for live performance
- **Two-column layout** - See more of the song at once (tablet/desktop)
- **Adjustable font size** - Make text larger or smaller on the fly
- **Metronome** - Visual and audio click track with BPM control
- **Lyrics-only mode** - Hide chords for vocalists
- **Show Numbers mode** - Display Nashville numbers instead of chords
- **Auto-scroll menu** - Controls auto-hide when scrolling

### 🔴 Live Mode (Auto-Advance)
- **Section-based progression** - Automatically advances through song sections
- **Intelligent timing** - Calculates duration based on BPM and measures
- **Transport controls** - Previous/Play-Pause/Next section navigation
- **Progress bar** - Visual indicator of section completion
- **Font controls** - Adjust text size during performance
- **Metronome integration** - Visual beats with optional audio click
- **Responsive layout** - Optimized controls for mobile and desktop

### 📱 Mobile Responsive
- **Phone optimized** - Clean sidebar with hamburger menu
- **Tablet friendly** - Touch controls and readable text
- **Desktop ready** - Full feature set with optimal layout
- **Touch-friendly controls** - Large buttons for live performance

---

## 🚀 Getting Started

### Web Version (Easiest)

1. **Download** `index.html` to your device
2. **Open** it in any modern web browser:
   - Chrome, Safari, Firefox, Edge
   - Works on Windows, Mac, iOS, Android
3. **Add to Home Screen** (mobile):
   - iOS: Share → Add to Home Screen
   - Android: Menu → Add to Home Screen
4. **Start creating songs!**

### Mac App Version

1. **Download** `ToneBook.app.zip`
2. **Extract** the zip file
3. **Drag** ToneBook.app to your Applications folder
4. **Open** ToneBook (right-click → Open if security prompt appears)
5. Songs are saved in your browser's localStorage

### Online Version

Access directly at: **https://dach2591-hue.github.io/ToneBook/**
- No installation needed
- Works on any device with internet
- Share URL with your worship team

---

## 📖 How to Use

### Creating a Song

1. Click **"+ New Song"** button
2. Enter song **Title**
3. Add **Content** with chords and lyrics:
   ```
   Intro

   Verse 1
   G            D
   Amazing grace how sweet the sound
   Em           C
   That saved a wretch like me
   ```
4. Set **Key**, **BPM**, and **Time Signature**
5. Add **measures count** for each section (for Live Mode):
   ```
   Intro
   //8 measures
   
   Verse 1
   //16 measures
   G            D
   Amazing grace how sweet the sound
   ```
6. Click **"Save Song"**

### Song Format

ToneBook recognizes:
- **Section headers**: Any line with text (e.g., "Verse 1", "Chorus", "Bridge")
- **Chords**: Capital letters with optional modifiers (G, Am, D7, Cmaj7, F#m)
- **Lyrics**: Regular text lines
- **Measures**: Lines starting with `//` followed by number (e.g., `//8 measures` or `//8 compases`)

### Organizing Songs

- **Create folders**: Click "+ New Folder" button
- **Add to folders**: Click folder icon on song → Select folders
- **Multiple folders**: Songs can be in multiple folders at once
- **Pin songs**: Click pin icon to keep songs at the top

### Performance Mode

1. Click **"Performance"** button on any song
2. Use controls to:
   - Toggle between chords/lyrics/numbers
   - Transpose up or down
   - Adjust font size
   - Start metronome
   - Switch between 1 or 2 columns
3. Scroll or tap **LIVE button** to enter Live Mode

### Live Mode (Auto-Advance)

1. Enter **Performance Mode** first
2. Click **LIVE** button (red with pulse indicator)
3. Controls:
   - **Font ±**: Adjust text size
   - **🎵 ON/OFF**: Toggle metronome
   - **🔇/🔊**: Mute/unmute metronome audio
   - **⏮**: Previous section
   - **▶/⏸**: Play/Pause auto-advance
   - **⏭**: Next section
   - **Exit**: Return to Performance Mode
4. Sections advance automatically based on measures and BPM
5. Progress bar shows completion for current section

### Mobile Usage

**On Phone/Tablet:**
- Tap **hamburger menu (☰)** to open song list
- Select a song → Sidebar closes automatically
- Tap **X in sidebar** to close menu
- All controls optimized for touch

**Tips:**
- Use 1-column view on phones for easier reading
- 2-column works great on tablets in landscape
- Font controls are in the menu bar (scroll if needed)
- Live Mode controls stack vertically on narrow screens

---

## 🎹 Chord Format

ToneBook recognizes various chord formats:

**Major chords:** C, D, E, F, G, A, B  
**Minor chords:** Cm, Dm, Em (or Cmin, Dmin, Emin)  
**Seventh chords:** C7, D7, Gmaj7, Am7  
**Suspended:** Csus, Dsus4, Gsus2  
**Diminished:** Cdim, Ddim7  
**Augmented:** Caug  
**Add chords:** Cadd9, Dadd11  
**Slash chords:** C/E, G/B, D/F#  
**Sharps/Flats:** C#, Db, F#m, Bbmaj7  

---

## 🔢 Nashville Number System

Toggle between chords and numbers for easier transposition and communication:

**In Key of C:**
- C = 1
- Dm = 2m
- Em = 3m
- F = 4
- G = 5
- Am = 6m
- Bdim = 7dim

**Benefits:**
- Transpose instantly to any key
- Universal notation for any musician
- Focus on chord function rather than specific notes

---

## ⚙️ Settings & Options

### Song Metadata
- **Original Key**: Set the song's original key (A, B, C, D, E, F, G with sharps/flats)
- **BPM**: Beats per minute (for metronome and Live Mode timing)
- **Time Signature**: 4/4, 3/4, 6/8, etc. (affects metronome beats)

### Display Modes
- **Show Chords**: Full chord notation above lyrics
- **Lyrics Only**: Hide chords (for vocalists/screens)
- **Show Numbers**: Nashville Number System

### Metronome
- **Visual**: Animated dots showing beats
- **Audio**: Optional click sound
- **BPM adjustment**: ±5 BPM increments
- **Time signature**: Automatically highlights beat 1

### Font Sizing
- **Range**: 50% to 200%
- **10% increments**: Fine control over text size
- **Independent**: Separate settings for Performance and Live modes

---

## 💾 Data Storage

### Local Storage
- All songs saved in browser's localStorage
- No internet required after initial load
- Data persists between sessions
- Automatic save on every edit

### Import/Export
- **Export format**: JSON-based `.tone` files
- **Export all songs**: One file with entire library
- **Export single song**: Individual song files
- **Import**: Merge songs with existing library (smart duplicate detection)
- **Backup**: Regular exports recommended

### Privacy
- All data stored locally on your device
- No cloud storage or account required
- No data collection or tracking
- Complete offline capability

---

## 🎯 Use Cases

### Worship Leaders
- Manage setlists with folders (e.g., "Sunday Service", "Youth Night")
- Transpose songs to match vocalist's range
- Display lyrics on screens (Lyrics Only mode)
- Auto-advance through song sections during live performance

### Musicians
- Keep personal songbook organized
- Practice with metronome
- Learn songs in different keys
- Quick reference during rehearsals

### Worship Teams
- Share song library via export/import
- Consistent chord notation across team
- Individual members can transpose to their preference
- Use Nashville numbers for quick communication

### Solo Artists
- Portable songbook on any device
- Performance mode for gigs
- Quick key changes between songs
- Professional presentation

---

## 📱 Device Compatibility

### Tested On:
- ✅ **iOS** (iPhone, iPad) - Safari, Chrome
- ✅ **Android** (Phone, Tablet) - Chrome, Firefox
- ✅ **Windows** - Chrome, Edge, Firefox
- ✅ **Mac** - Safari, Chrome, Firefox
- ✅ **Mac App** - Standalone application

### Minimum Requirements:
- Modern web browser (2020 or newer)
- JavaScript enabled
- LocalStorage enabled
- Screen resolution: 320px width minimum

### Recommended:
- Tablet or larger for Performance Mode
- Landscape orientation for 2-column view
- Touch screen for mobile controls

---

## 🔧 Troubleshooting

### Songs Not Saving
- Check if browser allows localStorage
- Disable "Private/Incognito" mode
- Check browser storage quota
- Try exporting songs and reimporting

### Chords Not Transposing
- Ensure chords are properly formatted (capital letter)
- Check original key is set correctly
- Verify chord notation (use standard formats)

### Performance Mode Issues
- Refresh the page
- Check font size settings
- Try different display mode
- Clear browser cache

### Mobile Sidebar Issues
- Use hamburger menu (☰) to open
- Tap X button to close
- Tap outside sidebar to close
- Tap song to select and auto-close

### Live Mode Not Auto-Advancing
- Ensure measures are set for each section (`//8 measures`)
- Check BPM is set for the song
- Verify time signature
- Press Play button (▶)

---

## 🆘 Support

### Common Questions

**Q: Can multiple people use the same song library?**  
A: Yes! Export your library and share the `.tone` file. Others can import it.

**Q: Does this work offline?**  
A: Yes! After initial load, everything works offline. Songs are stored locally.

**Q: Can I use this on multiple devices?**  
A: Yes, but you'll need to export from one device and import to another to sync songs.

**Q: Is my data backed up?**  
A: No automatic backup. Export your songs regularly as backup.

**Q: Can I customize the app?**  
A: Yes! The HTML file can be edited. It's open source.

### Getting Help

- Check this README first
- Review the troubleshooting section
- Export your songs before making changes
- Test in a different browser if issues persist

---

## 🎼 Tips & Best Practices

### Song Entry
- Use consistent section naming (Verse 1, Chorus, Bridge)
- Add measure counts for Live Mode functionality
- Include original key in metadata
- Set accurate BPM for metronome

### Performance
- Test songs in Performance Mode before live use
- Adjust font size before starting (not during song)
- Practice with Live Mode before using in service
- Have backup plan (printed lyrics/chords)

### Organization
- Create folders for different services/events
- Use pin feature for frequently used songs
- Export library regularly as backup
- Name songs consistently for easy search

### Collaboration
- Share exported songs with team members
- Use Nashville numbers for easier communication
- Set standard keys for your team
- Export setlists for specific services

---

## 🔄 Version History

### v10.8 (Current) - Final Release
- ✅ Close button inside sidebar header
- ✅ Font controls working on all devices
- ✅ Improved two-column balance algorithm
- ✅ Live Mode mobile layout optimized
- ✅ Hamburger menu fully functional
- ✅ Mobile responsive sidebar

### v10.7
- Fixed sidebar visibility on mobile
- Improved hamburger menu behavior

### v10.6
- Removed CSS !important blocking font controls
- Font sizing now works on mobile/tablet

### v10.5
- Added font controls to Performance Mode
- Improved column balancing algorithm

### Earlier Versions
- Performance Mode with metronome
- Live Mode with auto-advance
- Nashville Number System
- Import/Export functionality
- Folder organization
- Mobile responsive design

---

## 📄 License

ToneBook is free to use for personal and ministry purposes.

### You May:
- Use it for worship leading
- Share it with your team
- Modify the code for your needs
- Host it on your own website

### Please:
- Keep it free for ministry use
- Share improvements with others
- Give credit where appropriate

---

## 🙏 Credits

**Developed for worship leaders and musicians worldwide.**

Special thanks to:
- Worship leaders who tested and provided feedback
- Musicians who helped refine the features
- The open-source community

**Technologies Used:**
- React (via Babel standalone)
- Tailwind CSS
- Lucide React Icons
- HTML5 LocalStorage API

---

## 📞 Contact

For questions, feedback, or feature requests:
- GitHub: https://github.com/dach2591-hue/ToneBook
- Issues: Submit via GitHub Issues

---

## 🎸 Happy Worship Leading!

**ToneBook v10.8** - Making worship leading easier, one song at a time.

---

**Last Updated:** January 16, 2026  
**Version:** 10.8 (Final)  
**Status:** Production Ready ✅
