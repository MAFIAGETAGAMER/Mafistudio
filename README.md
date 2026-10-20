# Mafistudio — versión verificada

Diseño estático compatible con GitHub Pages. No requiere build, npm o dependencias externas.

## Instalar
Sube **el contenido** de esta carpeta (no la carpeta misma) a la raíz del repositorio `Mafistudio` de GitHub, reemplazando versiones anteriores. Debes subir `index.html`, `assets/`, el resto de imágenes y `mafiflow/privacy.html`.

## Cambios confirmados
- La barra superior muestra únicamente el texto Mafistudio, sin iconos añadidos.
- El logo de la tarjeta «Sobre» ahora es pequeño y mantiene su proporción: se genera del PNG original `SOLOLOGO4K.png`, se recorta sin alterar sus formas y se renderiza a **175 px de ancho máximo** en escritorio (135 px en móvil).
- El enlace «Inicio» ahora hace scroll al principio de la página desde cualquier sección; el objetivo `#top` ya no está sobre la cabecera fija.
- El eslogan se traduce en **español, inglés, francés, alemán y bengalí** usando el selector. Español es el idioma inicial de una instalación nueva; las preferencias guardadas tienen prioridad.
- CSS y JavaScript llevan **nombres de archivo exclusivos para esta versión**, evitando recibir código antiguo desde la caché del navegador.
- Se mantienen los juegos, enlaces, otras secciones, tema oscuro/claro y `mafiflow/privacy.html`.

## Editar
- `index.html`: estructura y enlaces.
- `assets/styles-mafistudio-v4.css`: estilos.
- `assets/app-mafistudio-v4.js`: traducciones e interacciones.
- `assets/mafistudio-emblema-v4.webp`: emblema recortado sin modificar su dibujo.

## Revisar después de subir
Abre `https://mafiagetagamer.github.io/Mafistudio/`, elige ES y comprueba que el lema sea «NO JUGAMOS PARA CAER BIEN. JUGAMOS MEJOR.». Luego haz clic en «Sobre» y en «Inicio» para verificar la navegación. Si GitHub Pages aún sirve el despliegue antiguo, espera a que termine el workflow de Pages y actualiza la página.
