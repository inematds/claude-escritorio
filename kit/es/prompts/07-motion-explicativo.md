# Prompt 7 — la idea en movimiento (Claude Motion)

**Plan:** Motion está en **beta** y solo está disponible en los planes **Team y Enterprise** (en Team viene activado; en Enterprise, el propietario debe activarlo). Quienes tienen el plan gratis, Pro o Max todavía no tienen acceso.
**Qué es:** una animación corta hecha con código (texto, gráficos, formas e imágenes), que se reproduce como un video y se descarga en MP4. No usa un generador de video: no crea filmaciones ni personas generadas por IA. Cambia una palabra, un número o el tiempo, y el resto queda igual.
**Dónde:** pestaña Artifacts › modelo Motion, escribe `/motion` en el cuadro de mensaje o ve a "Output" › Motion.

```
/motion Convierte este informe en una animación de 30 segundos para la reunión del equipo.
- Usa el design system [NOMBRE].
- Muestra solo 3 números: [A], [B], [C], cada uno con su etiqueta y la comparación con el mes pasado.
- Ritmo: un número cada 8 a 10 segundos, con tiempo para leer.
- Termina con una frase: [siguiente paso].
[PEGA EL INFORME O ADJÚNTALO]
```

**Ajustes:** «haz más grande el número 2», «deja la última frase en pantalla 2 segundos más», «cambia “clientes” por “pacientes”». Para seguir trabajando en el resultado, ábrelo en los editores de video que Claude indique al exportarlo.