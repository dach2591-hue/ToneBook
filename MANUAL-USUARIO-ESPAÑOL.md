# ToneBook - Manual de Usuario (Español)

**Versión**: 10.10  
**Fecha**: 19 de Enero, 2026  
**Creado por**: Daniel  

---

## Tabla de Contenido

1. [Introducción](#introducción)
2. [Comenzando](#comenzando)
3. [Funciones Principales](#funciones-principales)
4. [Gestión de Canciones](#gestión-de-canciones)
5. [Modo Performance](#modo-performance)
6. [Modo Live](#modo-live)
7. [Consejos y Mejores Prácticas](#consejos-y-mejores-prácticas)
8. [Solución de Problemas](#solución-de-problemas)

---

## Introducción

**ToneBook** es una aplicación web completa diseñada para líderes de alabanza y músicos. Te ayuda a organizar canciones, transponer acordes y mejorar la experiencia de alabanza en vivo con funciones como:

- Gestión de canciones con organización por carpetas
- Transposición de acordes y Sistema de Números Nashville
- Modo Performance con metrónomo
- Modo Live con avance automático de secciones
- Diseño responsive para tablets y teléfonos

---

## Comenzando

### Versión Web

1. Visita: https://dach2591-hue.github.io/ToneBook/
2. La app funciona completamente en tu navegador
3. No requiere instalación
4. Funciona en desktop, tablet y móvil

### App Mac

1. Descarga `ToneBook-Mac-v10.10.app.zip`
2. Extrae el archivo ZIP
3. Arrastra `ToneBook.app` a tu carpeta Aplicaciones
4. Haz doble clic para abrir
5. Si aparece advertencia de seguridad, ve a Preferencias del Sistema → Seguridad y Privacidad → Abrir de Todas Formas

### Configuración Inicial

1. **Crea tu primera canción**:
   - Click en "New Song"
   - Ingresa título, tonalidad, BPM y compás
   - Agrega acordes y letra usando el formato: `[Am]` para acordes

2. **Importa canciones existentes**:
   - Click en menú hamburguesa (☰)
   - Selecciona "Import Songs"
   - Elige tu archivo JSON

---

## Funciones Principales

### Formato de Canciones

ToneBook usa un formato de texto simple:

```
[Intro x2]
//8 compases
[Am] [F] [C] [G]

[Verso 1]
[C]Sublime [G]gracia del [Am]Señor [F]
[C]Que a un [G]infeliz salvó [C]

[Coro]
[F]Cuan grande [C]es [G]Dios
```

**Elementos clave**:
- `[NombreAcorde]` - Acordes
- `[Nombre Sección]` - Encabezados de sección (Intro, Verso, Coro, etc.)
- `//8 compases` - Conteos de compases para Modo Live
- `x2` - Indicadores de repetición

### Secciones Soportadas

- Intro
- Verse / Verso
- Chorus / Coro
- Bridge / Puente
- Outro
- Pre-Chorus
- Instrumental
- Interlude / Interludio
- Solo

---

## Gestión de Canciones

### Crear Canciones

1. Click en **"New Song"**
2. Completa:
   - **Title**: Nombre de la canción
   - **Key**: Tonalidad original (ej: C, Db, G#)
   - **BPM**: Tempo (opcional)
   - **Time Signature**: ej: 4/4, 3/4, 6/8 (opcional)
3. Ingresa **Letra y Acordes** en el área de texto
4. Click **"Save"**

### Organizar Canciones

**Fijar Canciones** (Crear Setlists):
1. Click en el ícono 📍 junto a cualquier canción
2. Las canciones fijadas aparecen arriba
3. Reordenar canciones fijadas:
   - **Desktop**: Arrastra usando el ícono ≡
   - **Móvil/Tablet**: Usa los botones ↑↓

**Carpetas** (Próximamente):
- Actualmente, usa títulos con prefijos
- Ejemplo: "Domingo-01-Sublime Gracia"

### Editar Canciones

1. Click en una canción para verla
2. Click en botón **"Edit"**
3. Realiza cambios
4. Click **"Save"**

### Eliminar Canciones

1. Click en una canción
2. Click en botón **"Delete"**
3. Confirma eliminación

### Importar/Exportar

**Exportar**:
1. Click en menú hamburguesa (☰)
2. Selecciona "Export Songs"
3. Se descarga archivo JSON con todas tus canciones

**Importar**:
1. Click en menú hamburguesa (☰)
2. Selecciona "Import Songs"
3. Elige archivo JSON
4. Las canciones se fusionan con las existentes (se saltan duplicados)

---

## Modo Performance

El Modo Performance muestra tu canción en un formato limpio y legible para la alabanza.

### Entrar a Modo Performance

1. Abre cualquier canción
2. Click en botón **"Performance"**
3. La pantalla muestra la canción con controles

### Funciones del Modo Performance

#### Menú Auto-Oculto (5 segundos)
- El menú desaparece después de 5 segundos
- **Aparece barra de info** arriba con:
  - Título de canción (izquierda)
  - Key, Tempo, Time (derecha)
  - Metrónomo (debajo del título cuando está activo)
- Toca en cualquier parte para mostrar menú nuevamente

#### Modos de Visualización

**Show Chords** (predeterminado):
```
[C]Sublime [G]gracia
```

**Lyrics Only**:
```
Sublime gracia
```

**Show Numbers** (Nashville):
```
[1]Sublime [5]gracia
```

#### Transponer

- Click **-** para transponer hacia abajo
- Click **+** para transponer hacia arriba
- Muestra: "Original: C, Current: D"
- Los acordes se actualizan automáticamente
- Respeta la armadura (bemoles en tonalidades con bemoles, sostenidos en tonalidades con sostenidos)

#### Metrónomo

1. Click **"Play"** para iniciar metrónomo
2. Muestra beats visuales (●●○○)
3. Click de audio (puedes silenciar con 🔇)
4. Ajusta BPM con botones - / +
5. Cuando el menú está oculto, el metrónomo aparece debajo del título

#### Distribución en Columnas

- Alterna entre **1 columna** y **2 columnas**
- 2 columnas útil para canciones cortas
- Balanceo automático

#### Tamaño de Fuente

- Click **-** para disminuir
- Click **+** para aumentar
- Rango: 50% a 200%

#### Navegación Entre Canciones

Cuando las canciones están fijadas:
- **◀ Prev** - Canción anterior en setlist
- **1/5** - Posición actual
- **▶ Next** - Siguiente canción en setlist
- Permanece en Modo Performance al cambiar canciones

---

## Modo Live

El Modo Live proporciona avance automático de secciones, perfecto para canciones complejas con múltiples secciones.

### Configurar para Modo Live

**Formatea tu canción con secciones**:
```
[Intro x2]
//16 compases
[C] [G] [Am] [F]

[Verso 1]
//8 compases
[C]Sublime [G]gracia...

[Coro]
//8 compases
[F]Cuan grande [C]es [G]Dios
```

**Requerido**:
- Encabezados de sección: `[Intro]`, `[Verso 1]`, etc.
- Conteos de compases: `//8 compases`, `//16 compases`

**Opcional**:
- Indicadores de repetición: `x2`, `x3`

### Entrar a Modo Live

1. Entra primero a Modo Performance
2. Click en botón **"LIVE"** (rojo con pulso)
3. Se activa Modo Live

### Funciones del Modo Live

#### Header (Cuando Está Detenido)
- **Título de canción** e información
- **Controles de fuente** (- / +)
- **Metrónomo** toggle (🎵 ON/OFF)
- **◀ 1/5 ▶** - Navegar canciones
- **Exit Live** - Regresar a Modo Performance

#### Header Auto-Oculto (Cuando Está Sonando)
- Presiona **▶ Play**
- El header se desliza hacia arriba y desaparece
- El contenido llena toda la pantalla
- Toca en cualquier parte para mostrar header temporalmente

#### Visualización de Sección

Muestra la sección actual con:
- **Nombre de sección** (grande, azul)
- **Conteo de compases** "16 compases (8 × 2)"
- **Duración** "38s"
- **Acordes y letra** (fuente grande)
- **Siguiente sección** vista previa abajo

#### Controles de Transporte (Flotantes)

Cuando el header está visible:
- **⏮** - Sección anterior
- **▶** o **⏸** - Play/Pausa
- **⏭** - Siguiente sección

Los controles están centrados y flotan sobre el contenido.

#### Avance Automático

1. Presiona **▶ Play**
2. La sección se reproduce por la duración calculada
3. La barra de progreso muestra el tiempo restante (verde)
4. Avanza automáticamente a la siguiente sección
5. Se detiene en la sección final

**Cálculo de duración**:
- Basado en: compases × repetición × compás ÷ BPM
- Ejemplo: 8 compases × 2 repeticiones × 4/4 ÷ 120 BPM = 32 segundos

#### Metrónomo en Modo Live

- Beats visuales durante reproducción (●●○○)
- Sincronizado con BPM
- Puedes silenciar audio con 🔇

---

## Consejos y Mejores Prácticas

### Entrada de Canciones

**Usa nombres de sección consistentes**:
- ✅ `[Verso 1]`, `[Verso 2]`
- ✅ `[Coro]`
- ✅ `[Puente]`
- ❌ `[V1]`, `[verso 1]`, `[VERSO UNO]`

**Notación de acordes**:
- ✅ `[C]`, `[Am]`, `[Gmaj7]`
- ✅ `[Db]`, `[C#]`
- ❌ `C`, `Am` (sin corchetes)

**Líneas de compases para Modo Live**:
```
[Intro]
//8 compases
```
Siempre pon la línea de compases justo después del encabezado de sección.

### Crear Setlists

1. **Fija canciones en orden**:
   - Click 📍 en cada canción
   - Aparecen arriba en orden

2. **Reordena según necesites**:
   - Desktop: Arrastra con ≡
   - Móvil: Usa flechas ↑↓

3. **Durante el servicio**:
   - Abre primera canción → Modo Performance
   - Usa **▶ Next** para avanzar por el setlist
   - Nunca salgas del Modo Performance

### Transposición

**Consejos**:
- Db y C# son equivalentes (elige según la armadura)
- Tonalidades con bemoles: F, Bb, Eb, Ab, Db, Gb
- Tonalidades con sostenidos: G, D, A, E, B, F#, C#
- ToneBook usa automáticamente la notación correcta

**Ejemplo**:
- Canción en Db (tonalidad con bemoles)
- Acordes: Db, Ebm, Gb
- Transponer +1 → D (tonalidad con sostenidos)
- Los acordes se convierten en: D, Em, G

### Flujo de Trabajo en Alabanza

**Flujo típico de servicio**:

1. **Antes del servicio**:
   - Crear/actualizar canciones
   - Fijar canciones en orden de setlist
   - Verificar tonalidades y BPM

2. **Durante el servicio**:
   - Abrir primera canción
   - Entrar a Modo Performance
   - El menú se auto-oculta después de 5s
   - La barra de info permanece visible (título, key, tempo)
   - Usar ▶ Next entre canciones
   - Entrar a Modo Live para canciones complejas

3. **Usando Modo Live**:
   - Presionar Play cuando estés listo
   - El header desaparece (pantalla completa)
   - Las secciones avanzan automáticamente
   - Tocar la pantalla para mostrar controles si es necesario
   - Usar ⏭ para saltar secciones manualmente

### Uso en Móvil/Tablet

**iPad/Tablet (horizontal)**:
- Mejor para liderar alabanza
- Tamaños de fuente más grandes
- Todas las funciones disponibles
- Usa soporte o holder

**iPhone/Móvil (vertical)**:
- Bueno para práctica
- Controles compactos
- Pantalla pequeña = menos visible a distancia

---

## Solución de Problemas

### Las Canciones No Se Guardan

**Problema**: Los cambios no persisten  
**Solución**: Verifica configuración de almacenamiento del navegador, no uses modo privado/incógnito

### Los Acordes No Transponen

**Problema**: Los acordes no cambian al transponer  
**Solución**: Asegúrate de que los acordes estén entre corchetes: `[Am]` no `Am`

### Modo Live No Funciona

**Problema**: Las secciones no se muestran  
**Solución**: 
- Verifica formato de sección: `[Intro]` o `[Verso 1]`
- Agrega conteos de compases: `//8 compases`

### El Metrónomo No Suena

**Problema**: No hay sonido del metrónomo  
**Solución**:
- Verifica volumen del dispositivo
- Asegúrate de que no esté silenciado (🔇 → 🔊)
- Algunos navegadores requieren interacción del usuario primero

### El Menú No Se Oculta

**Problema**: El menú permanece visible en Modo Performance  
**Solución**: 
- Espera 5 segundos sin interacción
- Toca la pantalla para alternar manualmente

### La App No Carga en Mac

**Problema**: Mensaje "La app está dañada"  
**Solución**:
1. Click derecho en app → Abrir
2. O: Preferencias del Sistema → Seguridad y Privacidad → Abrir de Todas Formas
3. O: Terminal: `xattr -cr /ruta/a/ToneBook.app`

### Importación Falló

**Problema**: La importación de JSON no funciona  
**Solución**:
- Asegúrate de que el archivo sea JSON válido
- La exportación de ToneBook crea el formato correcto
- Verifica que el archivo no esté corrupto

### No Puedo Reordenar Canciones

**Problema**: No puedo reordenar canciones fijadas  
**Solución**:
- **Desktop**: Usa el ícono ≡ para arrastrar
- **Móvil/Tablet**: Usa botones de flecha ↑↓
- Asegúrate de que las canciones estén fijadas primero

---

## Atajos de Teclado

*Próximamente en versiones futuras*

---

## Gestión de Datos

### Almacenamiento Local

- Todos los datos se guardan en el almacenamiento local del navegador
- Persiste entre sesiones
- Específico del navegador/dispositivo
- No se sincroniza entre dispositivos

### Estrategia de Respaldo

**Importante**: ¡Siempre haz respaldo de tus canciones!

1. **Exporta regularmente**:
   - Exportaciones semanales recomendadas
   - Antes de servicios importantes
   - Después de agregar muchas canciones

2. **Guarda exportaciones**:
   - Almacenamiento en la nube (Google Drive, Dropbox)
   - Múltiples ubicaciones
   - Nombres de archivo con fecha de versión

3. **Prueba importaciones**:
   - Verifica que las exportaciones funcionen
   - Prueba en diferentes dispositivos

---

## Requisitos del Sistema

### Versión Web

- **Navegador**: Chrome, Safari, Firefox, Edge (versiones recientes)
- **Almacenamiento**: ~5-10 MB para 100 canciones
- **Internet**: Solo para carga inicial (luego funciona offline)

### App Mac

- **OS**: macOS 10.13 o posterior
- **RAM**: 100 MB
- **Almacenamiento**: 50 MB

---

## Soporte y Comentarios

**¿Preguntas o problemas?**
- Revisa este manual primero
- Consulta la sección de solución de problemas
- Contacto: [tu información de contacto]

**¿Solicitudes de funciones?**
- ¡Nos encantaría escuchar tus ideas!
- Envía vía: [método de feedback]

---

## Historial de Versiones

### v10.10 (Enero 2026)
- Nueva barra de header centrada en Modo Performance
- Mejora en responsive móvil
- Corrección de problemas de superposición del header
- Integración mejorada del metrónomo

### v10.9 (Enero 2026)
- Correcciones probadas en servicio de iglesia
- Agregada navegación Prev/Next en Modo Live
- Corrección de visualización Db vs C#
- Reordenamiento de canciones en móvil

### v10.8 (Enero 2026)
- Mejoras en sidebar móvil
- Correcciones de controles de fuente
- Balanceo de dos columnas

---

## Créditos

**Creado por**: Daniel Chay Perea
**Versión**: 10.10  
**Última Actualización**: 19 de Enero, 2026

---

## Licencia

ToneBook se proporciona tal cual para uso personal y de alabanza.

---

**¡Feliz Liderazgo de Alabanza!** 🎸🙏✨
