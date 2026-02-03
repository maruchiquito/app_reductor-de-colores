Editor de Imágenes con Python y Streamlit

Aplicación web interactiva desarrollada con Python y Streamlit que permite cargar imágenes, aplicar múltiples filtros en el orden seleccionado por el usuario, analizar cambios visuales y descargar la imagen procesada.

El proyecto combina procesamiento de imágenes, análisis de colores y una interfaz amigable enfocada en la experimentación visual.

Funcionalidades principales

 Carga de imágenes (.jpg, .jpeg, .png)
Aplicación de filtros en el orden de selección
Visualización comparativa (imagen original vs procesada)
Extracción de paletas de colores dominantes
Análisis de: Dimensiones, Modo de color, Canales, Colores únicos, Tamaño en memoria.
Descarga de la imagen procesada
Limpieza y reinicio de filtros

Filtros disponibles
Escala de grises
Sketch (dibujo a lápiz)
Sepia
Invertido
Desenfoque (Blur)
Reducción de colores (K-Means)
Reducción de colores con efecto lápiz

El resultado final depende del orden en que se seleccionan los filtros, permitiendo múltiples combinaciones creativas.

Tecnologías utilizadas

- Python
- Streamlit
- OpenCV
- NumPy
- Pillow
- Scikit-learn (K-Means)
- Pandas


