# Ideas3D – separadores Megacracks 2026/27 (V2)

Objetivo: separadores delgados con pestaña superior, uno por equipo, siguiendo el dibujo del usuario, para colocar en la Box Premium Panini Megacracks 2026/27 ref. 28438. Dentro de cada equipo, cartas ordenadas por número.

## Geometría inicial (NO validada físicamente)
- Cuerpo: 92 × 60 mm
- Pestaña superior: 50 × 8 mm; desplazada a la derecha
- Altura total: 68 mm
- Grosor: 1,2 mm
- Formato: una pieza plana (sin doblez), con relieve de pestaña en el contorno.

Las medidas comerciales externas conocidas de la lata son aproximadamente 170 × 110 × 74 mm, pero **NO se dispone de una medición del volumen interior** ni de la posición final de las cartas. No es correcto garantizar que el modelo de 68 mm permita cerrar la lata. Antes de imprimir un juego completo, imprimir una muestra y probar cierre sin forzar. Dejar al menos 3–4 mm de holgura bajo la tapa tras comprobar la profundidad interior.

## Uso
1. Abre FreeCAD en Windows.
2. Macro → Macros… → elige `separadores_megacracks.FCMacro` y ejecútala.
3. Verás el separador de prueba de REAL MADRID. El archivo STL, si se exporta correctamente, se guardará en `Ideas3D_Megacracks_STL` dentro de tu carpeta de usuario.
4. Modifica los parámetros al principio de la macro. Para generar varios equipos, cambia `GENERAR_TODOS = True`.
5. Importa el STL en Bambu Studio, colócalo plano y haz una prueba con PLA+ antes de imprimir el resto.

**Importante:** La macro crea geometría 3D con nombre de equipo en el árbol de FreeCAD, pero NO graba letras sobre la pieza. La versión posterior puede implementar texto en relieve o alojamiento para etiquetas intercambiables.
