# ToneBook 🎸

**Your complete worship leader tool for practice and live performance**

## Version 10.2 - Mobile Optimized

This version includes full mobile and tablet responsive design fixes!

## Features

### 📚 Song Management
- Create, edit, and organize songs
- Folder organization with drag & drop
- Pin favorites for quick access
- Import/Export your entire library
- Local storage (never lose your songs)

### 🎵 Performance Mode
- Transpose chords to any key
- Nashville Number System support
- Lyrics-only view for singers
- Multiple display modes
- Font size controls
- Visual metronome with audio

### 🎬 Live Mode (Hands-Free Performance!)
- **Auto-advance** through song sections
- **Progress bar** shows timing for each section
- **Visual metronome** with pulsing dots
- **Audio metronome** (mute option available)
- **Font controls** for on-the-fly adjustments
- Perfect for live worship leading

### 📱 Mobile Responsive (NEW in v10.2!)
- **Mobile menu** - Sidebar slides in as overlay
- **Optimized controls** - All buttons properly sized for touch
- **Adaptive layout** - Stacks vertically on small screens
- **Centered transport** - Play/pause buttons stay centered
- Works perfectly on phones and tablets!

## Quick Start

### Installation

#### Web Version (Works Everywhere)
1. Download `tonebook-v10.2.zip` or just use `index.html`
2. Open `index.html` in your browser
3. Start using ToneBook!

#### Mac Version
1. Download `ToneBook-Mac-v10.2.app.zip`
2. Extract and drag `ToneBook.app` to Applications
3. Double-click to launch
4. Opens in Chrome as a standalone app

### Adding Your Songs
1. Click "New Song"
2. Add title, chords, and lyrics
3. Set BPM and time signature
4. Save!

### Organizing
- Create folders for different categories
- Drag songs to folders
- Pin frequently used songs

### Practice Mode
1. Select a song
2. Enter Performance Mode
3. Transpose to your key
4. Turn on metronome
5. Practice!

### Live Performance
1. Click "LIVE" button
2. Press PLAY ▶
3. Play hands-free!
4. Sections auto-advance based on measures and BPM

## Live Mode Tips

### Default Settings (Perfect for Performing)
- ✅ Metronome: ON (visual dots)
- ✅ Audio: MUTED (silent for audience)
- ✅ Font: 130% (easily readable)

### Controls
- **🎵 ON/OFF** - Toggle metronome visual
- **🔊/🔇** - Toggle metronome audio
- **Font: - / +** - Adjust text size
- **⏮** - Previous section
- **▶/⏸** - Play/Pause auto-advance
- **⏭** - Next section
- **Exit Live** - Return to performance mode

### How Auto-Advance Works
Each section displays its measure count and duration. The auto-advance timer uses:
- Measures in the section
- BPM from the song
- Time signature
- Repeat count

When a section completes, it automatically advances to the next section!

## Mobile Usage

### On Phones/Tablets
- **Menu Button** (☰) - Tap to open song library
- **Sidebar** - Slides in from left, tap outside to close
- **Performance Mode** - Buttons stack vertically
- **Live Mode** - Controls optimized for touch
- **Exit Button** - Always accessible in top-right corner

### Touch Controls
All buttons are properly sized for touch:
- Minimum 24px for small controls
- 32-40px for standard buttons
- 48px for primary actions (Play button)

## Song Format

ToneBook uses a simple text format with section markers:

```
[INTRO]
4x2
G  D  Em  C

[VERSO 1]
8
G            D
La atmósfera cambiando está
Em           C
Tu Espíritu está aquí

[CORO]
4x2
G        D
Es evidente tu mover
Em       C
Tu Espíritu está aquí
```

### Section Format
- `[SECTION NAME]` - Define sections (INTRO, VERSO, CORO, PUENTE, etc.)
- `4x2` - Measures × Repeats (4 measures, repeated 2 times = 8 total)
- Chords above lyrics
- Blank lines separate phrases

## Technical Details

- **Storage**: Local browser storage (localStorage)
- **File Format**: Single HTML file - no server required
- **Compatibility**: Modern browsers (Chrome, Firefox, Safari, Edge)
- **Offline**: Works completely offline
- **Data**: Import/Export JSON for backup
- **Mobile**: Fully responsive on all screen sizes

## Version History

**v10.2** - Mobile Responsive Update (Current)
- ✅ Full mobile and tablet responsive design
- ✅ Mobile menu with slide-in sidebar
- ✅ Optimized button sizes for touch
- ✅ Performance Mode header stacks on mobile
- ✅ Live Mode controls properly centered
- ✅ Exit button positioned correctly on all screens
- ✅ Improved spacing and layout for small screens

**v10.1** - Final Release
- Fixed: Performance Mode metronome button display
- Fixed: Mac app launch script
- Complete Live Mode with auto-advance
- Metronome with visual dots and audio
- Drag & drop to folders

**v10.0** - Complete Edition
- Live Mode with auto-advance
- Visual and audio metronome
- Progress tracking
- Hands-free operation

## Troubleshooting

### Mac App Won't Open
- Make sure Chrome is installed at: `/Applications/Google Chrome.app`
- Or it will try to open in your default browser
- Right-click the app and select "Open" if you get a security warning

### Songs Not Saving
- Make sure browser allows localStorage
- Try exporting your songs as backup (JSON file)

### Mobile Issues
- If sidebar doesn't open, make sure JavaScript is enabled
- If buttons overlap, try refreshing the page
- Clear browser cache if you see old version

### Metronome Not Working
- In Performance Mode: Click "⏵ Play" to start
- In Live Mode: Automatically ON, press ▶ to play

## Browser Support

Tested and working on:
- ✅ Chrome Desktop & Mobile
- ✅ Safari iOS & macOS
- ✅ Firefox Desktop & Mobile
- ✅ Edge Desktop
- ✅ Samsung Internet (Android)

## Credits

Created for worship leaders who need a reliable, feature-rich tool for both practice and live performance.

Version 10.2 includes comprehensive mobile responsive design improvements.

## License

Free to use for personal and church use.

---

**Enjoy making worship music! 🎵✨**

**Questions or feedback?** Feel free to reach out or open an issue on GitHub!
