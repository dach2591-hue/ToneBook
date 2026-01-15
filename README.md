# ToneBook 🎸

**Your complete worship leader tool for practice and live performance**

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

## Quick Start

### Installation

#### Web Version (Works Everywhere)
1. Download `tonebook-v10.1.zip`
2. Extract the files
3. Open `index.html` in your browser
4. Start using ToneBook!

#### Mac Version
1. Download `ToneBook-Mac-v10.1.app.zip`
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

### How Auto-Advance Works
Each section displays its measure count and duration. The auto-advance timer uses:
- Measures in the section
- BPM from the song
- Time signature
- Repeat count

When a section completes, it automatically advances to the next section!

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

## Version History

**v10.1** - Final Release (Current)
- Fixed: Performance Mode metronome button display
- Fixed: Mac app launch script
- Complete Live Mode with auto-advance
- Metronome with visual dots and audio
- Drag & drop to folders
- All features working perfectly!

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

### Metronome Not Working
- In Performance Mode: Click "⏵ Play" to start
- In Live Mode: Automatically ON, press ▶ to play

## Credits

Created for worship leaders who need a reliable, feature-rich tool for both practice and live performance.

## License

Free to use for personal and church use.

---

**Enjoy making worship music! 🎵✨**
