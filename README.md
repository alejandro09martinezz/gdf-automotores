# GDF Automotores — Web

## Deploy en Vercel + GitHub

1. Creá un repo en GitHub llamado `gdf-automotores`
2. Subí esta carpeta al repo
3. Entrá a vercel.com → New Project → importá el repo
4. Vercel lo detecta como sitio estático → Deploy automático

## Personalizar antes de subir

- **Teléfono**: buscar `XXXX-XXXX` y reemplazar con el número real
- **WhatsApp**: cambiar `5491100000000` por el número real (código de país + número sin 0 ni 15)
- **Dirección**: buscar `Dirección del taller` en el Schema.org del `<head>`
- **Mapa**: reemplazar el `src` del iframe con el embed real de Google Maps del taller
- **Imágenes**: agregar fotos reales en la carpeta `img/` con los nombres: `trabajo-1.webp` hasta `trabajo-6.webp`
- **Formulario**: el `action` del form ya tiene tu Formspree configurado

## Imágenes
Crear carpeta `img/` y agregar:
- `trabajo-1.webp` al `trabajo-6.webp` — fotos de trabajos realizados (560x420px mínimo)
- `og-image.jpg` — imagen para redes sociales (1200x630px)
