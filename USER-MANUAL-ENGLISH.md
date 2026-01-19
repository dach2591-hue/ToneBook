# ToneBook - User Manual (English)

**Version**: 10.10  
**Date**: January 19, 2026  
**Created by**: Daniel  

---

## Table of Contents

1. [Introduction](#introduction)
2. [Getting Started](#getting-started)
3. [Main Features](#main-features)
4. [Song Management](#song-management)
5. [Performance Mode](#performance-mode)
6. [Live Mode](#live-mode)
7. [Tips & Best Practices](#tips--best-practices)
8. [Troubleshooting](#troubleshooting)

---

## Introduction

**ToneBook** is a comprehensive web-based application designed for worship leaders and musicians. It helps you organize songs, transpose chords, and enhance live performance experiences with features like:

- Song management with folder organization
- Chord transposition and Nashville Number System
- Performance Mode with metronome
- Live Mode with automatic section advancement
- Mobile-responsive design for tablets and phones

---

## Getting Started

### Web Version

1. Visit: https://dach2591-hue.github.io/ToneBook/
2. The app runs entirely in your browser
3. No installation required
4. Works on desktop, tablet, and mobile

### Mac Desktop App

1. Download `ToneBook-Mac-v10.10.app.zip`
2. Extract the ZIP file
3. Drag `ToneBook.app` to your Applications folder
4. Double-click to open
5. If prompted about security, go to System Preferences → Security & Privacy → Open Anyway

### First Time Setup

1. **Create your first song**:
   - Click "New Song" button
   - Enter title, key, BPM, and time signature
   - Add chords and lyrics using the format: `[Am]` for chords

2. **Import existing songs**:
   - Click hamburger menu (☰)
   - Select "Import Songs"
   - Choose your JSON file

---

## Main Features

### Song Format

ToneBook uses a simple text format for songs:

```
[Intro x2]
//8 measures
[Am] [F] [C] [G]

[Verse 1]
[C]Amazing [G]grace how [Am]sweet the [F]sound
[C]That saved a [G]wretch like [C]me

[Chorus]
[F]How great [C]is our [G]God
```

**Key elements**:
- `[ChordName]` - Chords
- `[Section Name]` - Section headers (Intro, Verse, Chorus, etc.)
- `//8 measures` - Measure counts for Live Mode
- `x2` - Repeat indicators

### Supported Sections

- Intro
- Verse (Verso in Spanish)
- Chorus (Coro in Spanish)
- Bridge (Puente in Spanish)
- Outro
- Pre-Chorus
- Instrumental
- Interlude
- Solo

---

## Song Management

### Creating Songs

1. Click **"New Song"** button
2. Fill in:
   - **Title**: Song name
   - **Key**: Original key (e.g., C, Db, G#)
   - **BPM**: Tempo (optional)
   - **Time Signature**: e.g., 4/4, 3/4, 6/8 (optional)
3. Enter **Lyrics & Chords** in the text area
4. Click **"Save"**

### Organizing Songs

**Pinning Songs** (Creating Setlists):
1. Click the 📍 pin icon next to any song
2. Pinned songs appear at the top
3. Reorder pinned songs:
   - **Desktop**: Drag using the ≡ handle
   - **Mobile/Tablet**: Use ↑↓ arrow buttons

**Folders** (Coming Soon):
- Currently, use song titles with prefixes
- Example: "Sunday-01-Amazing Grace"

### Editing Songs

1. Click on a song to view it
2. Click **"Edit"** button
3. Make changes
4. Click **"Save"**

### Deleting Songs

1. Click on a song
2. Click **"Delete"** button
3. Confirm deletion

### Import/Export

**Export**:
1. Click hamburger menu (☰)
2. Select "Export Songs"
3. JSON file downloads with all your songs

**Import**:
1. Click hamburger menu (☰)
2. Select "Import Songs"
3. Choose JSON file
4. Songs merge with existing (duplicates skipped)

---

## Performance Mode

Performance Mode displays your song in a clean, readable format for performance.

### Entering Performance Mode

1. Open any song
2. Click **"Performance"** button
3. Screen shows song with controls

### Performance Mode Features

#### Auto-Hide Menu (5 seconds)
- Menu disappears after 5 seconds
- **Info bar appears** at top with:
  - Song title (left)
  - Key, Tempo, Time (right)
  - Metronome (below title when active)
- Tap anywhere to show menu again

#### Display Modes

**Show Chords** (default):
```
[C]Amazing [G]grace
```

**Lyrics Only**:
```
Amazing grace
```

**Show Numbers** (Nashville):
```
[1]Amazing [5]grace
```

#### Transpose

- Click **-** to transpose down
- Click **+** to transpose up
- Display shows: "Original: C, Current: D"
- Chords update automatically
- Respects key signature (flats in flat keys, sharps in sharp keys)

#### Metronome

1. Click **"Play"** to start metronome
2. Visual beats show (●●○○)
3. Audio click (can mute with 🔇)
4. Adjust BPM with - / + buttons
5. When menu hidden, metronome appears below song title

#### Column Layout

- Toggle between **1 column** and **2 columns**
- 2 columns useful for shorter songs
- Automatic balancing

#### Font Size

- Click **-** to decrease
- Click **+** to increase
- Range: 50% to 200%

#### Navigation Between Songs

When songs are pinned:
- **◀ Prev** - Previous song in setlist
- **1/5** - Current position
- **▶ Next** - Next song in setlist
- Stays in Performance Mode when changing songs

---

## Live Mode

Live Mode provides automatic section advancement, perfect for complex songs with multiple sections.

### Setting Up for Live Mode

**Format your song with sections**:
```
[Intro x2]
//16 measures
[C] [G] [Am] [F]

[Verse 1]
//8 measures
[C]Amazing [G]grace...

[Chorus]
//8 measures
[F]How great [C]is our [G]God
```

**Required**:
- Section headers: `[Intro]`, `[Verse 1]`, etc.
- Measure counts: `//8 measures`, `//16 measures`

**Optional**:
- Repeat indicators: `x2`, `x3`

### Entering Live Mode

1. Enter Performance Mode first
2. Click **"LIVE"** button (red with pulse)
3. Live Mode activates

### Live Mode Features

#### Header (When Stopped)
- **Song title** and info
- **Font controls** (- / +)
- **Metronome** toggle (🎵 ON/OFF)
- **◀ 1/5 ▶** - Navigate songs
- **Exit Live** - Return to Performance Mode

#### Auto-Hide Header (When Playing)
- Press **▶ Play**
- Header slides up and disappears
- Content fills entire screen
- Tap anywhere to show header temporarily

#### Section Display

Shows current section with:
- **Section name** (large, blue)
- **Measure count** "16 measures (8 × 2)"
- **Duration** "38s"
- **Chords and lyrics** (large font)
- **Next section** preview at bottom

#### Transport Controls (Floating)

When header visible:
- **⏮** - Previous section
- **▶** or **⏸** - Play/Pause
- **⏭** - Next section

Controls are centered and float above content.

#### Automatic Advancement

1. Press **▶ Play**
2. Section plays for calculated duration
3. Progress bar shows time remaining (green)
4. Automatically advances to next section
5. Stops at final section

**Duration calculation**:
- Based on: measures × repeat × time signature ÷ BPM
- Example: 8 measures × 2 repeats × 4/4 ÷ 120 BPM = 32 seconds

#### Metronome in Live Mode

- Visual beats during playback (●●○○)
- Synced with BPM
- Can mute audio with 🔇

---

## Tips & Best Practices

### Song Entry

**Use consistent section names**:
- ✅ `[Verse 1]`, `[Verse 2]`
- ✅ `[Chorus]`
- ✅ `[Bridge]`
- ❌ `[V1]`, `[verse 1]`, `[VERSE ONE]`

**Chord notation**:
- ✅ `[C]`, `[Am]`, `[Gmaj7]`
- ✅ `[Db]`, `[C#]`
- ❌ `C`, `Am` (without brackets)

**Measure lines for Live Mode**:
```
[Intro]
//8 measures
```
Always put measure line right after section header.

### Creating Setlists

1. **Pin songs in order**:
   - Click 📍 on each song
   - They appear at top in order

2. **Reorder as needed**:
   - Desktop: Drag with ≡
   - Mobile: Use ↑↓ arrows

3. **During service**:
   - Open first song → Performance Mode
   - Use **▶ Next** to move through setlist
   - Never leave Performance Mode

### Transposition

**Tips**:
- Db and C# are equivalent (choose based on key signature)
- Flat keys: F, Bb, Eb, Ab, Db, Gb
- Sharp keys: G, D, A, E, B, F#, C#
- ToneBook automatically uses correct notation

**Example**:
- Song in Db (flat key)
- Chords: Db, Ebm, Gb
- Transpose +1 → D (sharp key)
- Chords become: D, Em, G

### Performance Workflow

**Typical service flow**:

1. **Before service**:
   - Create/update songs
   - Pin songs in setlist order
   - Check keys and BPM

2. **During service**:
   - Open first song
   - Enter Performance Mode
   - Menu auto-hides after 5s
   - Info bar stays visible (title, key, tempo)
   - Use ▶ Next between songs
   - Enter Live Mode for complex songs

3. **Using Live Mode**:
   - Press Play when ready
   - Header disappears (full screen)
   - Sections auto-advance
   - Tap screen to show controls if needed
   - Use ⏭ to skip sections manually

### Mobile/Tablet Usage

**iPad/Tablet (landscape)**:
- Best for worship leading
- Larger font sizes
- All features available
- Use stand or holder

**iPhone/Mobile (portrait)**:
- Good for practice
- Compact controls
- Smaller screen = less visible from distance

---

## Troubleshooting

### Songs Not Saving

**Problem**: Changes don't persist  
**Solution**: Check browser storage settings, don't use private/incognito mode

### Chords Not Transposing

**Problem**: Chords don't change when transposing  
**Solution**: Make sure chords are in brackets: `[Am]` not `Am`

### Live Mode Not Working

**Problem**: Sections don't show  
**Solution**: 
- Check section format: `[Intro]` or `[Verse 1]`
- Add measure counts: `//8 measures`

### Metronome Not Playing

**Problem**: No sound from metronome  
**Solution**:
- Check device volume
- Make sure not muted (🔇 → 🔊)
- Some browsers require user interaction first

### Menu Not Hiding

**Problem**: Menu stays visible in Performance Mode  
**Solution**: 
- Wait 5 seconds without interaction
- Tap screen to manually toggle

### App Not Loading on Mac

**Problem**: "App is damaged" message  
**Solution**:
1. Right-click app → Open
2. Or: System Preferences → Security & Privacy → Open Anyway
3. Or: Terminal: `xattr -cr /path/to/ToneBook.app`

### Import Failed

**Problem**: JSON import doesn't work  
**Solution**:
- Make sure file is valid JSON
- Export from ToneBook creates correct format
- Check file isn't corrupted

### Reordering Songs Not Working

**Problem**: Can't reorder pinned songs  
**Solution**:
- **Desktop**: Use ≡ drag handle
- **Mobile/Tablet**: Use ↑↓ arrow buttons
- Make sure songs are pinned first

---

## Keyboard Shortcuts

*Coming in future versions*

---

## Data Management

### Local Storage

- All data stored in browser's local storage
- Persists between sessions
- Specific to browser/device
- Not synced across devices

### Backup Strategy

**Important**: Always backup your songs!

1. **Export regularly**:
   - Weekly exports recommended
   - Before important services
   - After adding many songs

2. **Save exports**:
   - Cloud storage (Google Drive, Dropbox)
   - Multiple locations
   - Version-dated filenames

3. **Test imports**:
   - Verify exports work
   - Test on different devices

---

## System Requirements

### Web Version

- **Browser**: Chrome, Safari, Firefox, Edge (latest versions)
- **Storage**: ~5-10 MB for 100 songs
- **Internet**: Only for initial load (then works offline)

### Mac App

- **OS**: macOS 10.13 or later
- **RAM**: 100 MB
- **Storage**: 50 MB

---

## Support & Feedback

**Questions or issues?**
- Check this manual first
- Review troubleshooting section
- Contact: [your contact info]

**Feature requests?**
- We'd love to hear your ideas!
- Submit via: [feedback method]

---

## Version History

### v10.10 (January 2026)
- New centered header bar in Performance Mode
- Improved mobile responsiveness
- Fixed header overlap issues
- Enhanced metronome integration

### v10.9 (January 2026)
- Church service testing fixes
- Added Prev/Next navigation in Live Mode
- Fixed Db vs C# display
- Mobile song reordering

### v10.8 (January 2026)
- Mobile sidebar improvements
- Font controls fixes
- Two-column balancing

---

## Credits

**Created by**: Daniel  
**Version**: 10.10  
**Last Updated**: January 19, 2026

---

## License

ToneBook is provided as-is for personal and worship use.

---

**Happy Worship Leading!** 🎸🙏✨
