# 🎸 ToneBook v11.3.4

**The Complete Worship Leader & Musician App**

ToneBook is a powerful web-based application designed for worship leaders and musicians to organize songs, transpose chords, and enhance live performance experiences.

[![Live Demo](https://img.shields.io/badge/demo-live-brightgreen)](https://yourusername.github.io/ToneBook/)
[![Version](https://img.shields.io/badge/version-11.3.4-blue)](https://github.com/yourusername/ToneBook)
[![License](https://img.shields.io/badge/license-MIT-green)](LICENSE)

[🇺🇸 English](#english) | [🇪🇸 Español](#español)

---

## English

### 🚀 Quick Start (5 Minutes!)

1. **Fork or Download** this repository
2. **Upload to GitHub**:
   - Create new repo named `ToneBook`
   - Upload `index.html`
3. **Enable GitHub Pages**:
   - Settings → Pages
   - Source: `main` branch, `/ (root)` folder
   - Save
4. **Done!** Visit: `https://yourusername.github.io/ToneBook/`

### ✨ What's New in v11.3.4

#### 🗑️ **Bulk Delete System**
- Delete entire library with confirmation
- Delete all songs by specific artist
- Delete all songs in custom folder
- Perfect for cleaning up imports

#### 🎥🎵 **Dual Video/Audio Embeds**
- Add YouTube videos for visual reference
- Add Spotify/Apple Music for audio practice
- Toggle between video and audio
- Fixed player stays visible while scrolling
- Only in practice view (not Performance/Live modes)

#### 📋 **Menu Reorganization**
- Intuitive icon menu (collapsed)
- Logical section order (expanded)
- Consistent navigation experience

#### 📖 **Bilingual Help System**
- Complete guide in English and Spanish
- Toggle language on the fly
- Includes all new features

### 🎵 Core Features

#### Song Management
- ✅ Create and edit songs with chords, lyrics, metadata
- ✅ Automatic chord detection and transposition
- ✅ Sections: `[Intro]`, `[Verse]`, `[Chorus]`, `[Bridge]`
- ✅ Comments with `--` for performance notes
- ✅ Nashville Number System support

#### Organization
- ✅ **Artist-Based**: Automatic grouping by artist
- ✅ **Custom Folders**: Create setlists and collections
- ✅ **Global Search**: Find any song by title, artist, or key
- ✅ **Pin Songs**: Create ordered setlists
- ✅ **Drag & Drop**: Organize easily (desktop)

#### Performance Mode
- ✅ Clean, distraction-free view for live performance
- ✅ Real-time chord transposition
- ✅ Multiple views: Chords, Lyrics Only, Numbers
- ✅ Adjustable font size (50%-200%)
- ✅ Built-in metronome with visual indicator
- ✅ Navigate between songs with Prev/Next buttons

#### Live Mode
- ✅ Automatic section advancement based on BPM
- ✅ Visual progress bar for each section
- ✅ Transport controls (play/pause/next/previous)
- ✅ Perfect for rehearsals and performances

#### Practice Enhancement
- ✅ **Video Embed**: YouTube videos for visual reference
- ✅ **Audio Embed**: Spotify/Apple Music for practice
- ✅ **Dual Mode**: Toggle between video and audio
- ✅ **Fixed Player**: Stays visible while scrolling song
- ✅ **Smart Detection**: Auto-converts URLs and iframe codes

#### Import/Export
- ✅ Export entire library or by artist/folder
- ✅ Smart import with duplicate detection
- ✅ Automatic folder creation
- ✅ Share setlists with your band (.tone files)

#### Bulk Delete
- ✅ Delete entire library (with safety confirmation)
- ✅ Delete all songs by artist
- ✅ Delete all songs in folder
- ✅ Perfect for cleaning up old imports

### 📖 Quick Guide

#### Creating Songs

```
Title: Amazing Grace
Artist: John Newton
Key: C
BPM: 80
Time Signature: 3/4
Video Embed: https://youtu.be/VIDEO_ID
Audio Embed: https://open.spotify.com/track/TRACK_ID

[Intro]
//4 measures

[Verse 1]
[C]Amazing [G]grace
-- Piano only, soft and gentle
[Am]How [F]sweet the sound
-- Build dynamics gradually

[Chorus]
//8 measures
[C]That saved a [G]wretch like [Am]me
```

**Syntax:**
- Chords: `[C]`, `[Am]`, `[G7]`, `[Csus4]`
- Sections: `[Intro]`, `[Verse 1]`, `[Chorus]`, `[Bridge]`
- Comments: `-- Your performance note here`
- Measures: `//8 measures` (for Live Mode timing)
- Embeds: Paste YouTube or Spotify links/iframes

#### Adding Video/Audio

**YouTube:**
1. Go to video on YouTube
2. Click Share → Copy link
3. Paste in "Video Embed" field
4. Can also paste full iframe code

**Spotify:**
1. Go to track on Spotify
2. Click Share → Embed track → Copy code
3. Paste in "Audio Embed" field
4. Can also paste just the track URL

**Apple Music:**
1. Share → Copy link
2. Paste in "Audio Embed" field

#### Using Embeds
- Add one or both (video + audio)
- If both exist, toggle buttons appear
- Player fixed on right side
- Only in main view (not Performance/Live)
- YouTube works best on GitHub Pages
- Spotify works great locally (no ads with login)

### 🛠️ Technical Details

- **Framework**: React (via Babel standalone)
- **Styling**: Tailwind CSS (via CDN)
- **Storage**: Browser LocalStorage (client-side only)
- **File Format**: Single HTML file (no build process)
- **Export Format**: `.tone` files (JSON)
- **Size**: ~250 KB
- **Requirements**: Modern web browser

### 📦 What's Included

```
ToneBook-v11.3.4/
├── index.html              ⭐ Main application (REQUIRED)
├── README.md               📄 This file
├── CHANGELOG.md            📝 Version history
├── DEPLOYMENT.md           🚀 Deployment guide
├── LICENSE                 📄 MIT License
└── .gitignore              🔧 Git configuration
```

### 💾 Data & Backup

**Important**: Your data is stored locally in your browser's LocalStorage.

**To Backup:**
1. Click Export → Export All Songs
2. Save the `.tone` file
3. Do this regularly!

**To Restore:**
1. Click Import Songs
2. Select your `.tone` backup
3. Choose merge or replace

### 🌟 Use Cases

**Worship Leaders:**
- Organize Sunday setlists
- Transpose for different vocalists
- Share songs with band members
- Practice with original tracks

**Musicians:**
- Learn new songs with video/audio
- Transpose to your instrument key
- Add performance notes
- Track your song library

**Worship Teams:**
- Share setlists easily
- Everyone has same chord charts
- Add practice tracks
- Collaborate on arrangements

### 🔒 Privacy & Security

- ✅ All data stored locally in your browser
- ✅ No server, no tracking, no analytics
- ✅ Export/import for backup
- ✅ Works completely offline
- ✅ Your songs stay private

### 📱 Mobile Support

- ✅ Fully responsive design
- ✅ Touch-friendly controls
- ✅ Works on tablets and phones
- ✅ Landscape mode recommended for tablets
- ✅ Add to home screen for app-like experience

### 🆘 Support

- 📖 **Help Modal**: Click ℹ️ icon (bilingual guide)
- 🐛 **Issues**: Open a GitHub issue
- 💬 **Questions**: GitHub Discussions
- 📧 **Contact**: [Your contact info]

### 🤝 Contributing

Contributions welcome! Please:
1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test thoroughly
5. Submit a pull request

### 📄 License

MIT License - Free for personal and ministry use.

---

## Español

### 🚀 Inicio Rápido (¡5 Minutos!)

1. **Fork o Descarga** este repositorio
2. **Sube a GitHub**:
   - Crea nuevo repo llamado `ToneBook`
   - Sube `index.html`
3. **Habilita GitHub Pages**:
   - Settings → Pages
   - Source: branch `main`, carpeta `/ (root)`
   - Guardar
4. **¡Listo!** Visita: `https://tuusuario.github.io/ToneBook/`

### ✨ Novedades en v11.3.4

#### 🗑️ **Sistema de Borrado Masivo**
- Borrar librería completa con confirmación
- Borrar todas las canciones de un artista
- Borrar todas las canciones de carpeta personalizada
- Perfecto para limpiar imports

#### 🎥🎵 **Embeds Duales Video/Audio**
- Agrega videos de YouTube para referencia visual
- Agrega Spotify/Apple Music para práctica de audio
- Alterna entre video y audio
- Reproductor fijo visible mientras scrolleas
- Solo en vista de práctica (no en modos Presentación/En Vivo)

#### 📋 **Reorganización del Menú**
- Menú de iconos intuitivo (colapsado)
- Orden lógico de secciones (expandido)
- Experiencia de navegación consistente

#### 📖 **Sistema de Ayuda Bilingüe**
- Guía completa en inglés y español
- Cambia idioma al vuelo
- Incluye todas las nuevas características

### 🎵 Características Principales

#### Gestión de Canciones
- ✅ Crear y editar canciones con acordes, letras, metadata
- ✅ Detección y transposición automática de acordes
- ✅ Secciones: `[Intro]`, `[Verso]`, `[Coro]`, `[Puente]`
- ✅ Comentarios con `--` para notas de presentación
- ✅ Soporte para Sistema de Números Nashville

#### Organización
- ✅ **Por Artista**: Agrupación automática por artista
- ✅ **Carpetas Personalizadas**: Crea setlists y colecciones
- ✅ **Búsqueda Global**: Encuentra canciones por título, artista o tono
- ✅ **Fijar Canciones**: Crea setlists ordenados
- ✅ **Arrastrar y Soltar**: Organiza fácilmente (escritorio)

#### Modo Presentación
- ✅ Vista limpia sin distracciones para presentación en vivo
- ✅ Transposición de acordes en tiempo real
- ✅ Múltiples vistas: Acordes, Solo Letras, Números
- ✅ Tamaño de fuente ajustable (50%-200%)
- ✅ Metrónomo integrado con indicador visual
- ✅ Navega entre canciones con botones Anterior/Siguiente

#### Modo En Vivo
- ✅ Avance automático de secciones basado en BPM
- ✅ Barra de progreso visual para cada sección
- ✅ Controles de reproducción (play/pausa/siguiente/anterior)
- ✅ Perfecto para ensayos y presentaciones

#### Mejora de Práctica
- ✅ **Video Embed**: Videos de YouTube para referencia visual
- ✅ **Audio Embed**: Spotify/Apple Music para práctica
- ✅ **Modo Dual**: Alterna entre video y audio
- ✅ **Reproductor Fijo**: Se mantiene visible mientras scrolleas
- ✅ **Detección Inteligente**: Auto-convierte URLs y códigos iframe

#### Importar/Exportar
- ✅ Exporta librería completa o por artista/carpeta
- ✅ Importación inteligente con detección de duplicados
- ✅ Creación automática de carpetas
- ✅ Comparte setlists con tu banda (archivos .tone)

#### Borrado Masivo
- ✅ Borrar librería completa (con confirmación de seguridad)
- ✅ Borrar todas las canciones de un artista
- ✅ Borrar todas las canciones de una carpeta
- ✅ Perfecto para limpiar imports antiguos

### 📖 Guía Rápida

#### Crear Canciones

```
Título: Sublime Gracia
Artista: John Newton
Tono: C
BPM: 80
Time Signature: 3/4
Video Embed: https://youtu.be/VIDEO_ID
Audio Embed: https://open.spotify.com/track/TRACK_ID

[Intro]
//4 measures

[Verso 1]
[C]Sublime [G]gracia
-- Solo piano, suave y gentil
[Am]Del Se[F]ñor
-- Construye dinámicas gradualmente

[Coro]
//8 measures
[C]Que a un in[G]feliz sal[Am]vó
```

**Sintaxis:**
- Acordes: `[C]`, `[Am]`, `[G7]`, `[Csus4]`
- Secciones: `[Intro]`, `[Verso 1]`, `[Coro]`, `[Puente]`
- Comentarios: `-- Tu nota de presentación aquí`
- Compases: `//8 measures` (para timing en Modo En Vivo)
- Embeds: Pega links o iframes de YouTube o Spotify

#### Agregar Video/Audio

**YouTube:**
1. Ve al video en YouTube
2. Click Compartir → Copiar enlace
3. Pega en campo "Video Embed"
4. También puedes pegar código iframe completo

**Spotify:**
1. Ve a la pista en Spotify
2. Click Compartir → Insertar pista → Copiar código
3. Pega en campo "Audio Embed"
4. También puedes pegar solo la URL de la pista

**Apple Music:**
1. Compartir → Copiar enlace
2. Pega en campo "Audio Embed"

#### Usar Embeds
- Agrega uno o ambos (video + audio)
- Si existen ambos, aparecen botones de alternancia
- Reproductor fijo en lado derecho
- Solo en vista principal (no Presentación/En Vivo)
- YouTube funciona mejor en GitHub Pages
- Spotify funciona excelente localmente (sin ads con login)

### 🛠️ Detalles Técnicos

- **Framework**: React (vía Babel standalone)
- **Estilos**: Tailwind CSS (vía CDN)
- **Almacenamiento**: LocalStorage del navegador (solo cliente)
- **Formato de Archivo**: Archivo HTML único (sin proceso de build)
- **Formato de Exportación**: Archivos `.tone` (JSON)
- **Tamaño**: ~250 KB
- **Requisitos**: Navegador web moderno

### 💾 Datos y Respaldo

**Importante**: Tus datos se guardan localmente en el LocalStorage de tu navegador.

**Para Respaldar:**
1. Click Exportar → Exportar Todas
2. Guarda el archivo `.tone`
3. ¡Hazlo regularmente!

**Para Restaurar:**
1. Click Importar Canciones
2. Selecciona tu respaldo `.tone`
3. Elige combinar o reemplazar

### 🌟 Casos de Uso

**Líderes de Alabanza:**
- Organizar setlists de domingo
- Transponer para diferentes vocalistas
- Compartir canciones con miembros de banda
- Practicar con pistas originales

**Músicos:**
- Aprender nuevas canciones con video/audio
- Transponer a tu tono de instrumento
- Agregar notas de presentación
- Seguir tu librería de canciones

**Equipos de Alabanza:**
- Compartir setlists fácilmente
- Todos tienen las mismas partituras
- Agregar pistas de práctica
- Colaborar en arreglos

### 🔒 Privacidad y Seguridad

- ✅ Todos los datos guardados localmente en tu navegador
- ✅ Sin servidor, sin tracking, sin analytics
- ✅ Exportar/importar para respaldo
- ✅ Funciona completamente offline
- ✅ Tus canciones permanecen privadas

### 📱 Soporte Móvil

- ✅ Diseño completamente responsive
- ✅ Controles amigables al tacto
- ✅ Funciona en tablets y teléfonos
- ✅ Modo horizontal recomendado para tablets
- ✅ Añade a pantalla principal para experiencia tipo app

### 🆘 Soporte

- 📖 **Modal de Ayuda**: Click en icono ℹ️ (guía bilingüe)
- 🐛 **Issues**: Abre un issue en GitHub
- 💬 **Preguntas**: GitHub Discussions
- 📧 **Contacto**: Daniel Chay Perea

### 📄 Licencia

Licencia MIT - Gratis para uso personal y ministerial.

---

## 📊 Version History

- **v11.3.4** - Bulk delete, dual video/audio embeds, menu reorder
- **v11.3** - Bilingual help, comments system, export improvements
- **v11.2** - 3-level menu structure
- **v11.0** - Artist-based organization
- **v10.x** - Core features and performance modes

See [CHANGELOG.md](CHANGELOG.md) for complete history.

---

### 📄 Autor

Daniel Chay Perea

**Made with ❤️ for worship leaders and musicians worldwide**  
**Hecho con ❤️ para líderes de alabanza y músicos en todo el mundo**

🎸 **ToneBook v11.3.4** - Worship Made Simple
