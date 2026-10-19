# Mafistudio — nueva página web

Rediseño del proyecto original de Mafistudio, inspirado visualmente en la plantilla `rbp-portfolio` proporcionada. Mantiene las imágenes, los enlaces, los proyectos y las traducciones del sitio original, pero está desarrollado en **HTML, CSS y JavaScript**. No requiere npm, Next.js, React, servidor especial, API ni servicios externos.

## Cómo verlo

Abre `index.html` con tu navegador o, para probarlo localmente con servidor:

```bash
python -m http.server 8000
```

Luego abre http://localhost:8000/.

## Publicarlo en GitHub Pages

1. Descomprime el ZIP del proyecto.
2. **Sube el contenido de la carpeta `Mafistudio-Redesign` a la raíz de tu repositorio `Mafistudio`**. No subas la carpeta contenedora, solo su contenido.
3. Si el repositorio ya tiene un `index.html`, reemplázalo con el nuevo. Conserva `assets/`, todas las imágenes y `mafiflow/privacy.html`.
4. En GitHub → **Settings** → **Pages** asegúrate de publicar la rama correcta y la carpeta `/(root)`.
5. Accede a https://mafiagetagamer.github.io/Mafistudio/ y actualiza la página si tu navegador mantiene una versión en caché.

**Antes de reemplazar**: haz una copia de la versión anterior o usa un commit de Git para poder volver atrás.

## Dónde editar

- `index.html`: estructura, enlaces, textos originales y contenido.
- `assets/styles.css`: colores, diseño responsive, secciones y animaciones.
- `assets/app.js`: traducciones, tema, interacciones y fondo WebGL.
- `assets/*.webp`: imágenes optimizadas para las tarjetas y el logo.
- `mafiflow/privacy.html`: **política de privacidad original, conservada sin modificaciones**.

## Características

- Fondo animado con shader WebGL inspirado en la plantilla, con degradado CSS si el equipo no puede usar WebGL.
- Navegación flotante, resaltado de sección, menú móvil y animaciones al desplazarse.
- Interacciones suaves y respeto a `prefers-reduced-motion`.
- Tema claro/oscuro, guardado en el navegador.
- Cinco idiomas originales: español, inglés, francés, alemán y bengalí. Se recuerda la selección del visitante.
- Tarjetas de RoomRush y Vaeryn con imágenes reales del ZIP aportado.
- Página de MafiFlow y todos los enlaces sociales originales.
- Metadatos para compartir y accesibilidad básica.

No se han copiado las fotografías, proyectos ficticios ni los datos personales de la plantilla de referencia.

## Observaciones

- Los enlaces a Discord y otros perfiles mantienen **exactamente** las direcciones originales; si cambian, actualízalos manualmente.
- Si editas directamente un texto dentro de `index.html`, ten en cuenta que algunos textos visibles se sustituyen por las traducciones de `assets/app.js` al cargar la página.
- La versión en vivo no se modifica hasta que tú subas los archivos a GitHub Pages.
