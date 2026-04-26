# Caja Personal — Guía de instalación

## Archivos incluidos
- `index.html` — la app completa
- `manifest.json` — configuración PWA
- `sw.js` — service worker (offline)

---

## Paso a paso: subir a GitHub Pages (gratis, 5 minutos)

### 1. Crear cuenta en GitHub
- Ve a https://github.com y crea una cuenta gratuita si no tienes.

### 2. Crear repositorio
- Clic en "+" (arriba a la derecha) → "New repository"
- Nombre: `caja-personal`
- Selecciona: **Public**
- Clic en "Create repository"

### 3. Subir los archivos
- En el repositorio recién creado, clic en "uploading an existing file"
- Arrastra o selecciona los 3 archivos: `index.html`, `manifest.json`, `sw.js`
- Clic en "Commit changes"

### 4. Activar GitHub Pages
- Ve a Settings (pestaña del repositorio) → Pages (menú izquierdo)
- En "Branch" selecciona: `main` → `/ (root)` → Save
- Espera 1-2 minutos. Tu URL quedará:
  `https://TU_USUARIO.github.io/caja-personal/`

---

## Instalar en Android como app

1. Abre Chrome en tu teléfono
2. Ve a la URL de tu GitHub Pages
3. Chrome mostrará automáticamente un banner: **"Agregar a pantalla de inicio"**
   - Si no aparece: menú ⋮ → "Agregar a pantalla de inicio"
4. Confirma. Aparece el ícono en tu pantalla de inicio.
5. Desde ahí abre sin barra de navegador, sin internet.

---

## Sobre los datos

- Se guardan en el almacenamiento local de Chrome en tu teléfono.
- No salen a ningún servidor. Son solo tuyos.
- Para no perderlos: usa **Respaldo JSON** periódicamente (guarda el archivo en Google Drive o donde prefieras).
- Para pasar a una IA: usa **Descargar CSV** — ese archivo lo puedes pegar directo en Claude, ChatGPT, o cualquier herramienta de análisis.

---

## Notas sobre los íconos

Los archivos `icon-192.png` e `icon-512.png` referenciados en el manifest son opcionales para que funcione la app — sin ellos Chrome usa un ícono genérico. Si quieres un ícono personalizado, sube dos imágenes PNG con esos nombres y dimensiones exactas.
