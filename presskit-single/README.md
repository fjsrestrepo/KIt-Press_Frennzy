# Press Kit — Artista Individual

Plantilla autónoma de press kit para un solo artista. Solo necesitás editar los datos y agregar las imágenes.

## 📁 Archivos

```
presskit-single/
  index.html      ← Abrí este archivo y editá la sección ARTIST
  images/         ← Poné acá las fotos del artista (.jpg o .png)
  README.md       ← Este instructivo
```

## 🚀 Cómo usar

### 1. Fotografías
Poné las fotos del artista en la carpeta `images/`. Podés nombrarlas como quieras (ej. `foto1.jpg`, `foto2.jpg`, etc.).

### 2. Editar datos
Abrí `index.html` en VS Code (o cualquier editor). Buscá esta línea:
```js
// ╔══════════════════════════════════════════╗
// ║  CONFIGURACIÓN — LLENÁ CON TUS DATOS    ║
// ╚══════════════════════════════════════════╝

const ARTIST = {
```

Ahí cambiás todos los valores:

- **name**: Nombre del artista
- **alias**: Apodo (o `null` si no tiene)
- **genre**: Género musical
- **city**: Ciudad, país
- **quote**: Frase que lo represente
- **phone**: WhatsApp de contacto (ej. `+57 300 123 4567`)
- **spotifyUrl**: Link de Spotify (o `"#"` si no tiene)
- **youtubeUrl**: Link de YouTube (o `null` si no tiene)
- **banner**: Las imágenes que pusiste en `images/` — ej. `["images/foto1.jpg", "images/foto2.jpg"]`
- **palette**: 6 colores en hexadecimal que representen al artista
- **stats**: 4 bloques con cifras (Spotify, Instagram, etc.)
- **release**: Nombre e info del último lanzamiento
- **bioShort**: Bio corta (1 párrafo)
- **bioLong**: Bio extendida (varios párrafos)
- **links**: Plataformas y redes sociales con sus URLs

### 3. Abrir en navegador
Doble clic en `index.html` para verlo. También podés subirlo a cualquier hosting (Netlify, Vercel, GitHub Pages, etc.).

## 🎨 Personalización de estilos
Si querés cambiar colores o tipografías, los estilos están en la sección `<style>` al inicio del archivo.

## 🟢 Botón de WhatsApp
El botón verde flotante usa el número de teléfono que configures. Al hacer clic abre WhatsApp con un mensaje automático.

---

Creado a partir del Press Kit de OK Press.