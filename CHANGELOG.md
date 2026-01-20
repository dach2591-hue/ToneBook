# Changelog

All notable changes to ToneBook will be documented in this file.

## [11.3.2] - 2026-01-20

### Fixed
- Export functionality now works correctly for all options (All Songs, Artists, Custom Folders)
- Search now properly searches across ALL songs regardless of selected folder
- Search results now display all matching songs (not just pinned ones)

### Changed
- Export menu redesigned with compact layout
- Export button in menu changed from "Export All" to "Export"
- Export organized into sections: All Songs / By Artist / By Custom Folder
- Artist and folder names in export menu now use smaller text for better scalability
- Export lists now have scroll when many items (max-height with overflow)
- Search results show counter: "Search Results (N)"

### Added
- Search documentation in Help modal (English and Spanish)
- Search now includes visual "Search Results" header when active
- All search results show pin and folder icons for quick actions

## [11.3.1] - 2026-01-20

### Added
- Comment system with `--` prefix for performance notes
- Comments appear in gray, smaller text, italic style
- Comments visible in all views: main view, Performance Mode, Live Mode
- Bilingual Help/Info modal (English/Spanish toggle)
- Complete user guide in both languages within the app
- Info button moved to bottom of collapsed menu

### Changed
- Help modal now includes language switcher
- All documentation available in English and Spanish
- Info button positioned after All Songs button in menu

### Documented
- Comment usage: `-- Piano here, keyboard only`
- Comment feature documented in Help modal (both languages)

## [11.3] - 2026-01-20

### Added
- Help/Info button (ℹ️) in collapsed menu
- Comprehensive bilingual user guide (English/Spanish)
- Export modal with organized sections (Artists/Custom Folders)
- UX improvements for folder expansion

### Changed
- Click on folder name OR chevron now expands/collapses folders
- Better mobile UX with larger touch targets
- Export menu shows all artists and folders with small, scrollable lists

### Fixed
- Mobile responsiveness for folder interactions
- Export menu organization and clarity

## [11.2] - 2026-01-20

### Added
- 3-level menu structure in sidebar
- "All Songs" submenu showing all songs alphabetically
- "Artists" submenu with artist folders
- "Custom Folders" submenu for user-created folders
- All submenus collapsed by default for cleaner interface

### Changed
- Complete reorganization of Songs section
- Songs now nested under their respective categories
- Alphabetical sorting of songs within all submenus
- Improved menu navigation with clearer hierarchy

### Improved
- Better organization for large song libraries
- Reduced visual clutter with collapsible submenus
- Faster navigation with organized structure

## [11.1.2] - 2026-01-20

### Added
- Delete button in edit mode for songs
- Confirmation dialog before deleting

### Changed
- Delete now accessible from edit screen (not just sidebar)

## [11.1.1] - 2026-01-20

### Added
- Custom Folders section (renamed from "Legacy Folders")
- Drag & drop support for songs → Custom Folders (desktop)
- Pin and folder icons on all nested songs

### Changed
- All folders and artist folders start collapsed by default
- Click anywhere on folder row to expand (not just chevron)
- "Legacy Folders" renamed to "Custom Folders"
- Chevron changed from button to div for better UX

### Fixed
- Mobile tap targets for folder expansion
- Folder collapse behavior on initial load

## [11.1] - 2026-01-20

### Added
- Export with folder names instead of IDs
- Import auto-creates folders from folder names
- Export by artist functionality
- Export by custom folder functionality
- Hierarchical song display (songs nested under folders)
- All songs in "All Songs" view shown nested and alphabetically sorted

### Changed
- Export JSON now includes `folderNames` array (readable names)
- Import handles both old format (folder IDs) and new format (folder names)
- Folders auto-created on import if they don't exist
- Songs only show when folder is expanded
- Pinned songs section at bottom shows only pinned from current context

### Improved
- Better organization for large libraries
- Cleaner interface with collapsible sections
- Easier sharing of songs with consistent folder structure across users

## [11.0.2] - 2026-01-20

### Added
- ToneBook icon (SVG) in header and collapsed menu
- Custom logo with book + musical note design

### Changed
- Header now shows ToneBook icon instead of text
- Collapsed menu shows icon when minimized

## [11.0.1] - 2026-01-20

### Fixed
- Collapsed menu display issues
- Icon rendering in different states

## [11.0] - 2026-01-20

### Added
- Artist-based organization system
- Artist field in song creation/editing
- Automatic artist folders in sidebar
- Artist folders collapsible/expandable
- Artist name displayed in song info throughout app
- Search includes artist names
- Songs auto-grouped by artist in sidebar

### Changed
- Sidebar now shows artist folders above custom folders
- "Unknown Artist" for songs without artist specified
- Artist folders sorted alphabetically (Unknown Artist at end)
- Complete reorganization of sidebar structure

### Migration
- Existing songs automatically assigned "Unknown Artist"
- No data loss - all songs preserved
- Artist field can be added to existing songs by editing

## [10.8] - 2026-01-20

### Fixed
- Mobile hamburger menu toggle functionality
- Font controls overlapping in mobile Performance Mode
- Column balancing algorithm for better mobile display
- Live Mode mobile interface improvements
- Close button added for better mobile navigation

### Changed
- Improved CSS specificity (removed !important declarations)
- Better character-count-based algorithm for column balancing
- Enhanced mobile user experience across all modes

## [10.7] - 2026-01-20

### Added
- Smart import with duplicate detection
- Options to keep, replace, or skip duplicates
- Automatic folder creation from imported song data
- Merge functionality (combines instead of replaces)

### Changed
- Import now merges with existing songs by default
- Better handling of folder references in imported songs
- Improved user feedback during import process

## [10.6] - 2026-01-20

### Added
- Export individual folders
- Export current folder option in export modal
- Better export organization with folder-specific exports

### Changed
- Export modal redesigned with multiple options
- Export all vs export folder choice

## [10.5] - 2026-01-20

### Added
- Prev/Next navigation buttons in Performance Mode
- Navigate through pinned songs during performance
- Keyboard shortcuts for navigation

### Changed
- Performance Mode header includes navigation controls
- Better song progression during live performance

## [10.4] - 2026-01-20

### Added
- Metronome functionality with visual and audio indicators
- BPM-based timing for metronome
- Play/pause metronome controls
- Mute audio option (keep visual indicator only)
- Live Mode with automatic section advancement
- Section-by-section progression based on measures and BPM
- Visual progress bar for each section
- Transport controls (play/pause/next/previous) for Live Mode

### Changed
- Performance Mode now includes metronome option
- Enhanced timing features for live performance

## [10.3] - 2026-01-20

### Added
- Pin/unpin songs for setlists
- Pinned songs appear at top of song list
- Drag & drop reordering for pinned songs (desktop)
- Arrow buttons for reordering pinned songs (mobile/tablet)
- Visual indicator (📌) for pinned songs

### Changed
- Pinned songs stay at top regardless of folder
- Better setlist management workflow

## [10.2] - 2026-01-20

### Added
- Mobile hamburger menu
- Responsive design improvements
- Touch-friendly controls for tablets and phones

### Fixed
- Layout issues on small screens
- Menu visibility on mobile devices

## [10.1] - 2026-01-20

### Added
- Multiple viewing modes: Chords, Lyrics Only, Nashville Numbers
- Chord to Nashville Number System conversion
- Font size adjustment (50% - 200%)
- Performance Mode with clean interface

### Changed
- Enhanced viewing experience for different use cases
- Better accessibility with font size controls

## [10.0] - 2026-01-20

### Added
- Basic song management (create, edit, delete)
- Chord transposition
- Folder organization
- Export/Import functionality (.tone files)
- Performance view with large text
- Copy to clipboard
- Export to PDF and Word

### Initial Features
- React-based single-page application
- LocalStorage for data persistence
- Chord detection and formatting
- Section support [Intro], [Verse], [Chorus], etc.
- Basic key detection

---

## Version Format

- Major version (11.x.x): Significant new features or breaking changes
- Minor version (x.3.x): New features, improvements
- Patch version (x.x.2): Bug fixes, small improvements
