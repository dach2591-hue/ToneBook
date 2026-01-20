# 🎸 ToneBook v11.3.2

**The Complete Worship Leader & Musician App**

ToneBook is a powerful web-based application designed for worship leaders and musicians to organize songs, transpose chords, and enhance live performance experiences.

[🇺🇸 English](#english) | [🇪🇸 Español](#español)

---

## English

### 🚀 Quick Start

1. **GitHub Pages Deployment** (Recommended)
   - Fork this repository or upload files to your GitHub repo
   - Go to Settings → Pages
   - Source: Deploy from branch `main` / `root`
   - Your app will be live at: `https://yourusername.github.io/ToneBook/`

2. **Local Use**
   - Simply open `index.html` in any modern web browser
   - All data stored locally in your browser

### ✨ Key Features

#### 🎵 Song Management
- Create and edit songs with chords, lyrics, and metadata
- Automatic chord detection and transposition
- Support for sections: `[Intro]`, `[Verse]`, `[Chorus]`, etc.
- Comments with `--` for performance notes (dynamics, cues, etc.)
- Nashville Number System support

#### 🎤 Organization by Artist
- Songs automatically grouped by artist
- Dynamic artist folders (no manual setup needed)
- Alphabetically sorted songs within each artist

#### 📁 Custom Folders
- Create custom folders for setlists (e.g., "Sunday Service", "Christmas")
- Drag & drop songs to folders (desktop)
- Pin songs to create ordered setlists

#### 🔍 Powerful Search
- Search across ALL songs by title, artist, or key
- Instant results regardless of selected folder
- Quick access to pin or move songs from search results

#### 🎭 Performance Mode
- Clean, distraction-free view for live performance
- Real-time chord transposition
- Switch between: Chords, Lyrics Only, Numbers (Nashville)
- Adjustable font size (50%-200%)
- Built-in metronome with visual indicator
- Navigate between songs with Prev/Next buttons

#### 🎬 Live Mode
- Automatic section advancement based on BPM and measures
- Visual progress bar for each section
- Transport controls (play/pause/next/previous)
- Perfect for rehearsals and performances

#### 📤 Export/Import
- **Export All Songs** - Complete library backup
- **Export by Artist** - Share specific artist songs
- **Export by Custom Folder** - Share setlists with your band
- Import with automatic folder creation
- Smart duplicate handling (keep, replace, or skip)

#### 🌍 Bilingual Support
- Complete interface available in English and Spanish
- Toggle language in Help/Info modal
- Documentation in both languages

#### 📱 Mobile Responsive
- Optimized for tablets and phones
- Touch-friendly controls
- Landscape mode recommended for tablets

### 📖 Usage Guide

#### Creating Songs
```
Title: Amazing Grace
Artist: John Newton
Key: C
BPM: 80
Time Signature: 3/4

[Verse 1]
[C]Amazing [G]grace
-- Piano here, keyboard only
[Am]How [F]sweet the sound
-- Crescendo for chorus

[Chorus]
//8 measures
[C]That saved a [G]wretch like [Am]me
```

**Chord Format**: `[C]`, `[Am]`, `[G7]`, `[Csus4]`  
**Sections**: `[Intro]`, `[Verse 1]`, `[Chorus]`, `[Bridge]`, `[Outro]`  
**Comments**: `-- Your note here` (appears in gray, smaller text)  
**Measures**: `//8 measures` (for Live Mode timing)

#### Organizing Your Library

1. **By Artist** - Automatic grouping
   - Add artist name when creating/editing songs
   - Artist folders appear automatically
   - Click artist name to view all songs

2. **Custom Folders** - Manual organization
   - Create folders for specific services or themes
   - Drag songs to folders (desktop)
   - Click 📁 icon to add songs (mobile/desktop)

3. **Pinned Songs** - Create Setlists
   - Click 📍 to pin songs
   - Pinned songs appear in order at bottom of sidebar
   - Drag to reorder (desktop) or use ↑↓ buttons (mobile)

#### Search
Type in the search box to find songs by:
- Song title (e.g., "Amazing Grace")
- Artist name (e.g., "Hillsong")
- Key (e.g., "C", "Am")

Results show ALL matching songs across your entire library.

#### Performance Tips
1. Pin songs in order to create your setlist
2. Use Performance Mode for clean, large-text view
3. Enable metronome for timing during practice
4. Add `-- comments` for dynamics and cues
5. Export setlists before important services as backup

### 🛠️ Technical Details

- **Framework**: React (via Babel standalone)
- **Styling**: Tailwind CSS (via CDN)
- **Storage**: Browser LocalStorage (client-side only)
- **File Format**: Single HTML file (no build process needed)
- **Export Format**: `.tone` files (JSON format)

### 📦 What's Included

```
tonebook-v11.3.2-complete/
├── index.html              - Main application (REQUIRED)
├── README.md               - This file
├── CHANGELOG.md            - Version history
├── DEPLOYMENT.md           - GitHub Pages setup guide
├── USER-GUIDE-EN.pdf       - User guide in English
├── USER-GUIDE-ES.pdf       - Guía de usuario en español
└── .gitignore              - Git configuration
```

### 🔄 Version History

- **v11.3.2** - Export fixes, compact menu, search improvements
- **v11.3** - Bilingual help, comments with --, UX improvements
- **v11.2** - 3-level menu structure (All Songs/Artists/Custom Folders)
- **v11.0** - Artist-based organization system
- **v10.8** - Mobile responsiveness fixes
- **v10.4** - Metronome and Live Mode

See [CHANGELOG.md](CHANGELOG.md) for complete history.

### 💾 Backup & Data

**Important**: Your data is stored locally in your browser's LocalStorage.

**To backup:**
1. Click Export → Export All Songs
2. Save the `.tone` file somewhere safe
3. Do this regularly, especially before browser updates

**To restore:**
1. Click Import Songs
2. Select your `.tone` backup file
3. Choose merge or replace option

### 🤝 Contributing

Found a bug or have a suggestion? Feel free to:
- Open an issue on GitHub
- Submit a pull request
- Contact the developer

### 📄 License

This project is open source and available for personal and ministry use.

---

## Español

### 🚀 Inicio Rápido

1. **Despliegue en GitHub Pages** (Recomendado)
   - Haz fork de este repositorio o sube los archivos a tu repo de GitHub
   - Ve a Settings → Pages
   - Source: Deploy from branch `main` / `root`
   - Tu app estará en: `https://tuusuario.github.io/ToneBook/`

2. **Uso Local**
   - Simplemente abre `index.html` en cualquier navegador moderno
   - Todos los datos se guardan localmente en tu navegador

### ✨ Características Principales

#### 🎵 Gestión de Canciones
- Crea y edita canciones con acordes, letras y metadata
- Detección y transposición automática de acordes
- Soporte para secciones: `[Intro]`, `[Verso]`, `[Coro]`, etc.
- Comentarios con `--` para notas de presentación (dinámicas, cues, etc.)
- Sistema de Números Nashville

#### 🎤 Organización por Artista
- Canciones agrupadas automáticamente por artista
- Folders dinámicos de artistas (sin configuración manual)
- Canciones ordenadas alfabéticamente dentro de cada artista

#### 📁 Carpetas Personalizadas
- Crea carpetas personalizadas para setlists (ej: "Domingo 21", "Navidad")
- Arrastra canciones a carpetas (escritorio)
- Fija canciones para crear setlists ordenados

#### 🔍 Búsqueda Potente
- Busca en TODAS las canciones por título, artista o tono
- Resultados instantáneos sin importar la carpeta seleccionada
- Acceso rápido para fijar o mover canciones desde resultados

#### 🎭 Modo Presentación
- Vista limpia sin distracciones para presentación en vivo
- Transposición de acordes en tiempo real
- Cambia entre: Acordes, Solo Letras, Números (Nashville)
- Tamaño de fuente ajustable (50%-200%)
- Metrónomo integrado con indicador visual
- Navega entre canciones con botones Anterior/Siguiente

#### 🎬 Modo En Vivo
- Avance automático de secciones basado en BPM y compases
- Barra de progreso visual para cada sección
- Controles de reproducción (play/pausa/siguiente/anterior)
- Perfecto para ensayos y presentaciones

#### 📤 Exportar/Importar
- **Exportar Todas** - Respaldo completo de tu librería
- **Exportar por Artista** - Comparte canciones de artista específico
- **Exportar por Carpeta** - Comparte setlists con tu banda
- Importa con creación automática de carpetas
- Manejo inteligente de duplicados (mantener, reemplazar o saltar)

#### 🌍 Soporte Bilingüe
- Interfaz completa disponible en inglés y español
- Cambia idioma en el modal de Ayuda/Info
- Documentación en ambos idiomas

#### 📱 Responsive Móvil
- Optimizado para tablets y teléfonos
- Controles táctiles amigables
- Modo horizontal recomendado para tablets

### 📖 Guía de Uso

#### Crear Canciones
```
Título: Sublime Gracia
Artista: John Newton
Tono: C
BPM: 80
Time Signature: 3/4

[Verso 1]
[C]Sublime [G]gracia
-- Piano aquí, solo teclado
[Am]Del Se[F]ñor
-- Crescendo para el coro

[Coro]
//8 measures
[C]Que a un in[G]feliz sal[Am]vó
```

**Formato de Acordes**: `[C]`, `[Am]`, `[G7]`, `[Csus4]`  
**Secciones**: `[Intro]`, `[Verso 1]`, `[Coro]`, `[Puente]`, `[Outro]`  
**Comentarios**: `-- Tu nota aquí` (aparece en gris, texto más pequeño)  
**Compases**: `//8 measures` (para timing en Modo En Vivo)

#### Organiza Tu Librería

1. **Por Artista** - Agrupación automática
   - Agrega nombre de artista al crear/editar canciones
   - Folders de artistas aparecen automáticamente
   - Click en nombre de artista para ver todas sus canciones

2. **Carpetas Personalizadas** - Organización manual
   - Crea carpetas para servicios específicos o temas
   - Arrastra canciones a carpetas (escritorio)
   - Click en icono 📁 para agregar canciones (móvil/escritorio)

3. **Canciones Fijadas** - Crear Setlists
   - Click en 📍 para fijar canciones
   - Canciones fijadas aparecen en orden al final del sidebar
   - Arrastra para reordenar (escritorio) o usa botones ↑↓ (móvil)

#### Búsqueda
Escribe en el cuadro de búsqueda para encontrar canciones por:
- Título de canción (ej: "Sublime Gracia")
- Nombre de artista (ej: "Hillsong")
- Tono (ej: "C", "Am")

Los resultados muestran TODAS las canciones coincidentes en toda tu librería.

#### Consejos de Presentación
1. Fija canciones en orden para crear tu setlist
2. Usa Modo Presentación para vista limpia con texto grande
3. Habilita metrónomo para timing durante práctica
4. Agrega comentarios `--` para dinámicas y cues
5. Exporta setlists antes de servicios importantes como respaldo

### 🛠️ Detalles Técnicos

- **Framework**: React (vía Babel standalone)
- **Estilos**: Tailwind CSS (vía CDN)
- **Almacenamiento**: LocalStorage del navegador (solo cliente)
- **Formato de Archivo**: Archivo HTML único (no requiere proceso de build)
- **Formato de Exportación**: Archivos `.tone` (formato JSON)

### 📦 Qué Incluye

```
tonebook-v11.3.2-complete/
├── index.html              - Aplicación principal (REQUERIDO)
├── README.md               - Este archivo
├── CHANGELOG.md            - Historial de versiones
├── DEPLOYMENT.md           - Guía de configuración GitHub Pages
├── USER-GUIDE-EN.pdf       - Guía de usuario en inglés
├── USER-GUIDE-ES.pdf       - Guía de usuario en español
└── .gitignore              - Configuración Git
```

### 🔄 Historial de Versiones

- **v11.3.2** - Correcciones de export, menú compacto, mejoras de búsqueda
- **v11.3** - Ayuda bilingüe, comentarios con --, mejoras UX
- **v11.2** - Estructura de menú de 3 niveles (Todas/Artistas/Carpetas)
- **v11.0** - Sistema de organización por artista
- **v10.8** - Correcciones responsive móvil
- **v10.4** - Metrónomo y Modo En Vivo

Ver [CHANGELOG.md](CHANGELOG.md) para historial completo.

### 💾 Respaldo & Datos

**Importante**: Tus datos se guardan localmente en el LocalStorage de tu navegador.

**Para respaldar:**
1. Click en Exportar → Exportar Todas
2. Guarda el archivo `.tone` en lugar seguro
3. Hazlo regularmente, especialmente antes de actualizaciones del navegador

**Para restaurar:**
1. Click en Importar Canciones
2. Selecciona tu archivo de respaldo `.tone`
3. Elige opción de combinar o reemplazar

### 🤝 Contribuir

¿Encontraste un bug o tienes una sugerencia? Siéntete libre de:
- Abrir un issue en GitHub
- Enviar un pull request
- Contactar al desarrollador

### 📄 Licencia

Este proyecto es código abierto y disponible para uso personal y ministerial.


### 📄 AUTOR

Daniel Chay Perea
---

**Made with ❤️ for worship leaders and musicians**  
**Hecho con ❤️ para líderes de alabanza y músicos**
