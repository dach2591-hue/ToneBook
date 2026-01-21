# Changelog

All notable changes to ToneBook will be documented in this file.

## [11.3.4] - 2026-01-21

### Added
- **Bulk Delete System**: Delete entire library, by artist, or by folder
- **Dual Video/Audio Embeds**: Add both YouTube and Spotify/Apple Music
- **Embed Toggle**: Switch between video and audio during practice
- **Fixed Player**: Embed stays visible while scrolling song
- **Smart URL Processing**: Auto-converts YouTube/Spotify URLs and iframe codes
- **Delete Icon**: Added 🗑️ to collapsed menu
- **Bilingual Help**: Complete documentation in English and Spanish for new features
- **YouTube Fallback**: Link to open in YouTube when embed fails

### Changed
- Menu order reorganized for better UX (Create → Songs → Export → Delete → Info)
- Both collapsed and expanded menus now have consistent order
- Help modal updated with Bulk Delete and Embeds sections
- Version bumped to v11.3.4 throughout app

### Fixed
- YouTube embed using youtube-nocookie.com for better compatibility
- Iframe extraction now checks first before URL processing
- Menu sections properly reordered in both views

### Security
- Bulk delete requires confirmation
- Delete entire library requires typing "DELETE"
- All deletions show song counts before confirming

## [11.3.3] - 2026-01-20

### Added
- Bulk delete menu section with Export-style organized list
- Delete entire library with double confirmation
- Delete by artist with confirmation
- Delete by folder with confirmation
- Warning banners about permanent deletion

### Fixed
- Export functionality for all export options
- Export menu now uses inline logic for proper scope

## [11.3.2] - 2026-01-20

### Fixed
- Export functionality now works correctly for all options
- Search now properly searches across ALL songs
- Search results display all matching songs, not just pinned ones

### Changed
- Export menu redesigned with compact layout
- Export organized into sections: All Songs / By Artist / By Custom Folder
- Artist and folder names use smaller text for scalability
- Export lists have scroll when many items
- Search results show counter

### Added
- Search documentation in Help modal

## [11.3.1] - 2026-01-20

### Added
- Comment system with `--` prefix for performance notes
- Comments appear in gray, smaller text, italic style
- Comments visible in all views
- Bilingual Help/Info modal (English/Spanish toggle)
- Complete user guide in both languages
- Info button moved to bottom of collapsed menu

### Documented
- Comment usage and examples
- All features documented in both languages

## [11.3] - 2026-01-20

### Added
- Help/Info button (ℹ️) in collapsed menu
- Comprehensive bilingual user guide
- Export modal with organized sections

### Changed
- Click on folder name OR chevron expands/collapses
- Better mobile UX with larger touch targets
- Export menu shows organized lists

### Fixed
- Mobile responsiveness for folder interactions

## [11.2] - 2026-01-20

### Added
- 3-level menu structure in sidebar
- "All Songs" submenu
- "Artists" submenu with artist folders
- "Custom Folders" submenu
- All submenus collapsed by default

### Changed
- Complete reorganization of Songs section
- Songs nested under categories
- Alphabetical sorting throughout

## [11.1.2] - 2026-01-20

### Added
- Delete button in edit mode
- Confirmation dialog before deleting

## [11.1.1] - 2026-01-20

### Added
- Custom Folders section (renamed from "Legacy Folders")
- Drag & drop support for songs → Custom Folders
- Pin and folder icons on nested songs

### Changed
- All folders start collapsed by default
- Click anywhere on folder row to expand
- Chevron changed to div for better UX

## [11.1] - 2026-01-20

### Added
- Export with folder names instead of IDs
- Import auto-creates folders from names
- Export by artist functionality
- Export by custom folder functionality
- Hierarchical song display
- All songs in "All Songs" nested and sorted

### Changed
- Export JSON includes `folderNames` array
- Import handles both old and new formats
- Folders auto-created on import

## [11.0.2] - 2026-01-20

### Added
- ToneBook icon (SVG) in header
- Custom logo with book + musical note

## [11.0] - 2026-01-20

### Added
- Artist-based organization system
- Artist field in song creation/editing
- Automatic artist folders
- Artist folders collapsible/expandable
- Artist name throughout app
- Search includes artist names

### Changed
- Sidebar shows artist folders above custom folders
- "Unknown Artist" for songs without artist
- Complete sidebar reorganization

## [10.8] - 2026-01-20

### Fixed
- Mobile hamburger menu toggle
- Font controls overlapping in mobile Performance Mode
- Column balancing for mobile
- Live Mode mobile interface

### Changed
- Improved CSS specificity
- Better column balancing algorithm
- Enhanced mobile UX

## [10.7] - 2026-01-20

### Added
- Smart import with duplicate detection
- Options to keep, replace, or skip duplicates
- Automatic folder creation from imported data
- Merge functionality

## [10.6] - 2026-01-20

### Added
- Export individual folders
- Export current folder option
- Better export organization

## [10.5] - 2026-01-20

### Added
- Prev/Next navigation buttons in Performance Mode
- Navigate through pinned songs
- Keyboard shortcuts for navigation

## [10.4] - 2026-01-20

### Added
- Metronome functionality
- BPM-based timing
- Play/pause metronome controls
- Mute audio option
- Live Mode with automatic section advancement
- Section progression based on measures and BPM
- Visual progress bar
- Transport controls

## [10.3] - 2026-01-20

### Added
- Pin/unpin songs for setlists
- Pinned songs at top
- Drag & drop reordering (desktop)
- Arrow buttons for reordering (mobile)
- Visual indicator (📌)

## [10.2] - 2026-01-20

### Added
- Mobile hamburger menu
- Responsive design improvements
- Touch-friendly controls

### Fixed
- Layout issues on small screens
- Menu visibility on mobile

## [10.1] - 2026-01-20

### Added
- Multiple viewing modes: Chords, Lyrics Only, Nashville Numbers
- Chord to Nashville Number conversion
- Font size adjustment (50% - 200%)
- Performance Mode

## [10.0] - 2026-01-20

### Initial Release
- Basic song management
- Chord transposition
- Folder organization
- Export/Import functionality
- Performance view
- Copy to clipboard
- Export to PDF and Word
- React-based SPA
- LocalStorage persistence
- Chord detection and formatting
- Section support

---

## Version Format

- Major version (11.x.x): Significant new features or breaking changes
- Minor version (x.3.x): New features, improvements
- Patch version (x.x.4): Bug fixes, small improvements
