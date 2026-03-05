# 🔐 Coberturas Cerraduras — PWA

Guía interactiva de coberturas de cerraduras para reparadores colaboradores.  
Funciona como **Progressive Web App** (PWA): instalable en Android, iOS y PC, y disponible **sin conexión** tras la primera carga.

---

## 📁 Estructura del repositorio

```
cerraduras-pwa/
├── index.html          ← App principal (toda la lógica y contenido)
├── manifest.json       ← Manifiesto PWA (nombre, iconos, colores)
├── sw.js               ← Service Worker (caché offline)
├── favicon.ico         ← Favicon multi-tamaño (16/32/48px)
├── og-image-wide.png   ← Imagen Open Graph para compartir (1200×630)
├── icons/
│   ├── icon-72.png
│   ├── icon-96.png
│   ├── icon-128.png
│   ├── icon-144.png
│   ├── icon-152.png
│   ├── icon-167.png
│   ├── icon-180.png
│   ├── icon-192.png
│   ├── icon-256.png
│   ├── icon-384.png
│   ├── icon-512.png
│   └── apple-touch-icon.png
└── README.md
```

---

## 🚀 Publicar en GitHub Pages

1. Crea un repositorio en GitHub (público o privado con Pages habilitado).
2. Sube **todos los archivos** manteniendo la estructura de carpetas.
3. Ve a **Settings → Pages → Source** y selecciona la rama `main` y carpeta `/ (root)`.
4. En pocos segundos tendrás la URL pública:  
   `https://<tu-usuario>.github.io/<nombre-repositorio>/`

---

## 📱 Instalar como app

### Android (Chrome)
1. Abre la URL en Chrome.
2. Pulsa el menú ⋮ → **"Añadir a pantalla de inicio"**.

### iOS (Safari)
1. Abre la URL en Safari.
2. Pulsa el botón compartir □↑ → **"Añadir a pantalla de inicio"**.

### PC (Chrome / Edge)
1. Abre la URL en Chrome o Edge.
2. Pulsa el icono ⊕ en la barra de direcciones → **"Instalar"**.

---

## ✅ Características

- **Offline first**: funciona sin conexión tras la primera carga gracias al Service Worker.
- **Instalable**: cumple todos los requisitos PWA (manifest + SW + HTTPS).
- **Responsive**: optimizado para móvil, tablet y escritorio.
- **Sin base de datos**: toda la información está embebida en el HTML — no requiere backend.
- **Ligero**: un único archivo HTML con todos los estilos y scripts inlineados.

---

## 🔒 Aviso legal

Herramienta de consulta con fines informativos, de uso exclusivo para reparadores colaboradores.  
No recoge datos ni interactúa con sistemas corporativos.  
No sustituye los canales o herramientas oficiales. De uso voluntario.
