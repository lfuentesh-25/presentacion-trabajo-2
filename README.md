# Filtrado digital de señales de audio — Grupo 9

Presentación interactiva ampliada para el Trabajo 2 de Señales y Sistemas. Incluye explicaciones, animaciones y un problema aplicado resuelto paso a paso.

## Archivos
- `index.html`: presentación, estilos, animaciones y simulaciones en un solo archivo.
- `README.md`: instrucciones de uso y publicación.

## Cómo abrir
1. Descomprime el ZIP.
2. Abre `index.html` con Chrome, Edge o Firefox actualizado.
3. Navega con los botones o las flechas del teclado.
4. En el laboratorio de audio, selecciona un archivo WAV, MP3 u otro formato compatible.

No requiere instalar programas, dependencias ni compilar código. Se recomienda conexión a Internet para cargar la fuente externa si el navegador la solicita; las simulaciones principales están incluidas en `index.html`.

## Publicar en GitHub Pages
1. Crea un repositorio público.
2. Sube `index.html` y `README.md` a la raíz.
3. Ve a **Settings → Pages**.
4. En **Build and deployment**, selecciona **Deploy from a branch**.
5. Elige `main` y la carpeta `/ (root)`. Guarda y espera la publicación.

## Contenido didáctico
- Qué es una señal de audio digital y cómo se realiza el muestreo.
- Cómo el ruido afecta una grabación.
- Qué significa filtrar y para qué se utiliza.
- Convolución discreta: interpretación de cada símbolo y ejemplo animado de suma ponderada.
- Respuesta en frecuencia y filtro pasa bajos.
- Diferencias conceptuales entre filtros FIR e IIR.
- Problema aplicado a una señal recibida en telecomunicaciones, resuelto con un filtro promedio de tres muestras.
- Resolución interactiva de la convolución, comparación entrada/salida y pregunta de autoevaluación.
- Laboratorio para cargar audio, ver las formas de onda original y filtrada, comparar dos formas de onda separadas y observar un cursor sincronizado con la reproducción y escuchar ambas versiones.
- Aplicaciones en procesamiento de audio y telecomunicaciones.

## Controles
- Ajustar el nivel de ruido de una señal ilustrativa.
- Avanzar o reproducir automáticamente los pasos de convolución.
- Resolver el problema aplicado paso a paso con ventana móvil animada y barra de salida que crece; comprobar una respuesta de autoevaluación.
- Cambiar la frecuencia de corte del gráfico pasa bajos.
- Cargar audio y aplicar filtros pasa bajos, pasa altos o pasa banda; la comparación visual se actualiza al cambiar el filtro o la frecuencia de corte; al reproducir cualquiera de las versiones, un cursor avanza sobre las dos señales.

## Consideraciones
- Los gráficos de muestreo, ruido y respuesta en frecuencia son simulaciones visuales didácticas.
- El laboratorio usa la API Web Audio del navegador y un filtro Biquad. Es una demostración práctica, no una implementación general de todos los filtros FIR/IIR.
- La señal procesada depende del audio cargado y de los controles elegidos.
