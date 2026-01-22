# 📋 ToneBook - Changelog

All notable changes to ToneBook will be documented in this file.

---

## [v11.4.1] - 2026-01-22

### ✨ Improvements

#### Enhanced Song Editor
- **Increased textarea height** from 384px (h-96) to 600px (h-[600px])
- **Better visibility** when editing songs with multiple verses
- **Enhanced editing experience** - see more content without scrolling
- **Added `text-sm`** class for better readability with larger content area

#### Custom Libraries Creation Improvements
- **Added "+ button** in Custom Libraries header
  - Quick access to create new libraries
  - Click the blue + icon next to "Custom Libraries"
  - Instant prompt to create library
  
- **Empty state handling**
  - When Custom Libraries section is empty, shows prominent "+ New Library" button
  - Better onboarding for new users
  - Clearer call-to-action to create first library

- **Streamlined Create menu**
  - Renamed "Create Song" → "Create"
  - Removed "+ New Library" from Create menu to reduce clutter
  - "+ New Song" remains as primary action
  - Custom Libraries creation moved to its own dedicated area

- **Bilingual library prompts**
  - English: "Library name?"
  - Spanish: "¿Nombre de la biblioteca?"
  - Uses `helpLanguage` variable for correct localization

#### Improved Documentation
- **Enhanced Custom Libraries section** in help modal (ℹ️)
- **English documentation** includes:
  - How to create libraries (click + button)
  - Examples: "Sunday Service", "Christmas", "Youth Night", "Rehearsal"
  - How to add songs to libraries (📁 icon or drag & drop)
  
- **Spanish documentation** includes:
  - Cómo crear bibliotecas (botón +)
  - Ejemplos: "Domingo 21", "Navidad", "Noche de Jóvenes", "Ensayo"
  - Cómo agregar canciones (icono 📁 o arrastrar y soltar)

### 🐛 Bug Fixes
- **Fixed Custom Libraries section visibility**
  - Section now properly shows even when no folders exist
  - Changed conditional from `{folders.length > 0 && (...)` to always render
  - Shows appropriate empty state with "+ New Library" button

- **Fixed JSX syntax errors**
  - Removed duplicate closing `</div>` tags
  - Corrected component structure

- **Fixed language variable references**
  - Changed `language` → `helpLanguage` throughout
  - Fixes "ReferenceError: language is not defined"
  - Proper bilingual support now working

- **Improved button layouts and spacing**
  - Better spacing in Create menu
  - Consistent hover states across all buttons
  - Uniform blue color scheme for all "New Library" actions

### 🔧 Technical Changes
- Updated version number to v11.4.1
- Improved React component structure for Custom Libraries
- Added conditional rendering for empty Custom Libraries state
- Inline folder creation implementation (no modal needed)
- Proper `helpLanguage` variable usage for localization

### 📝 UI/UX Improvements
- **Cleaner menu hierarchy**
  - Create menu focused on primary action (New Song)
  - Custom Libraries management in dedicated section
  
- **Better visual consistency**
  - All "New Library" buttons use blue color (`bg-blue-600`)
  - Consistent with overall app theme
  - Better contrast in both light and dark modes

- **Improved user flow**
  - More intuitive library creation process
  - Clear visual indicator (+ button) for creating libraries
  - Reduced cognitive load by separating concerns

---

## [v11.4.0] - 2026-01-21

### 🌙 Major Features

#### Dark Mode
- **Full dark mode implementation** throughout the application
- **Toggle button** in top-right corner (moon/sun icon)
- **Persistent preference** saved to localStorage
- **Optimized colors** for all UI elements in dark theme
- **Smooth transitions** between light and dark modes

#### Enhanced Export System
- **Web Share API integration** for mobile devices
  - Native share sheet on iOS (AirDrop, Messages, Mail, etc.)
  - Native share menu on Android (WhatsApp, Gmail, Drive, etc.)
  - Automatic fallback to download on desktop browsers

- **Multiple export options**:
  - Export All Songs
  - Export by Artist
  - Export by Custom Library
  - Export Current Song
  - All preserve folder structures during export

#### Import Improvements
- **Smart duplicate detection**
  - Shows preview of what will be imported
  - Highlights existing songs in red
  - Options: Skip, Replace, or Keep Both
  
- **Folder structure preservation**
  - Custom Libraries maintained during import
  - Songs retain their folder associations
  - Seamless library organization across devices

### ✨ UI/UX Improvements
- Better mobile responsiveness across all screen sizes
- Improved sidebar navigation with collapsible sections
- Enhanced performance mode with better controls
- Improved metronome visualization

---

## [v11.3.4] - 2026-01-20

### ✨ Features

#### Live Mode Enhancements
- **Auto-advance sections** based on BPM and time signature
- **Precise timing calculations** per section
- **Visual metronome** with beat counting display
- **Audio metronome** option with configurable sounds
- **Progress indicators** showing current section progress
- **Play/Pause/Stop controls** for precise timing control

#### Custom Libraries System
- **Create unlimited folders** for song organization
- **Drag & drop** songs into folders with visual feedback
- **Nested song display** under each library with sorting
- **Folder management** (create, rename, delete with confirmation)
- **Pin songs** within folders for quick access

#### Artists Organization
- **Automatic grouping** by artist name
- **Alphabetical sorting** of artists and songs
- **Song count** displayed per artist
- **Collapsible sections** for better navigation

---

#### Author

Daniel Chay Perea


---

## 📝 Version Numbering

- **Major** (11.x.x): Significant new features or breaking changes
- **Minor** (x.4.x): New features, enhancements, improvements
- **Patch** (x.x.1): Bug fixes, small improvements, refinements

---

**Last Updated**: January 22, 2026
