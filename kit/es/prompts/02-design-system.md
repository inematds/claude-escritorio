# Prompt 2 — tu marca se convierte en un design system

**Qué es un design system:** el «manual de marca» que Claude guarda y usa por su cuenta: colores, fuentes, logo,
espaciado y estilo de las imágenes. Lo configuras una vez; cada pieza posterior se crea con la identidad de tu marca.

**Qué necesita Claude (con una sola fuente basta para empezar):**
- un PDF o una presentación de una marca que te guste;
- capturas de las páginas principales de tu sitio;
- el logo (de preferencia, en versiones clara y oscura) y los nombres de las fuentes, si los sabes;
- si la marca está en código (un sitio en React, por ejemplo), el repositorio.

**Dónde:** en una conversación (adjunta los archivos) o en la configuración de Claude, en **Design systems** (en la app en inglés: Settings › Capabilities › Design systems › Manage).
El sitio independiente claude.ai/design dejará de funcionar el 14/12/2026; quienes tengan un design system allí pueden migrarlo desde la página Artifacts.

```
Adjunté [el PDF de la marca / capturas de mi sitio / mi logo]. Crea un design system de mi marca para que pueda usarlo
en documentos, presentaciones y piezas de diseño.

1. Extrae: paleta (con el código de color y el uso de cada color), fuentes para títulos y texto, uso del logo
   (sobre fondo claro y oscuro), espaciados, esquinas, estilo de íconos y estilo de fotos e ilustraciones.
2. Muéstrame una página de muestra: portada de presentación, una diapositiva de contenido, una publicación cuadrada y un botón.
3. Enumera lo que NO encontraste en los archivos (p. ej., «no hay una versión del logo para fondo oscuro») y pregúntame
   antes de inventarlo.
4. Escribe 5 reglas breves de «hacer / no hacer» para esta marca.
```

**Revísalo una vez:** el design system es aproximado. Comprueba los colores con el código oficial (si lo tienes) y
corrige lo que esté mal pidiéndolo en la conversación («el azul correcto es #1E40AF»).

Modelo de referencia: `../design-system-modelo.md`.