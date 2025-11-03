
# BLÏZ — AR Showroom Demo (Mock)

Este demo muestra el flujo visual de un showroom AR para el difusor BLÏZ Classic Walnut.
Incluye:
- Landing estática con "visor" simulado usando la foto real
- QR apuntando al URL de demo pensado en Vercel
- Snippet listo para incrustar cuando exista el modelo 3D (.glb/.usdz)

## Cómo publicar en Vercel (estático)
1. Crea un proyecto nuevo en Vercel y sube la carpeta `bliz_ar_showroom_demo/` como Static Site.
2. El archivo principal es `index.html`.
3. Cuando tengas el modelo 3D real, descomenta el bloque `<model-viewer>` del HTML y actualiza `src` con tu ruta.

## Reemplazar por modelo real
- Sube `bliz-classic-walnut.glb` a `/public/models/` de tu app Next.js o al storage que prefieras.
- Actualiza el `src` en el snippet y en `index.html`.

URL pensado para demo:
https://bliz-showroom-demo.vercel.app/c/classic-walnut

