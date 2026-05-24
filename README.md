# Visión por Computadora - TP2 : FFT y Métricas de Enfoque

### Autor

- Chechko, Víctor Nicolás **[110.901]**

### Resumen

La idea del trabajo es aplicar dos métricas de enfoque distintas a todos los frames de una secuencia de video (`focus_video.mov`), de forma tal que los algoritmos devuelvan automáticamente el frame de máximo enfoque detectado. Luego de realizar distintos procedimientos o experimentos, se comparan ambas y se extraen conclusiones.

La primer métrica es la presentada en el documento [Image Sharpness Measure for Blurred Images in Frequency Domain](https://www.sciencedirect.com/science/article/pii/S1877705813016007), y utiliza el contenido espectral de la imagen. La segunda corresponde a la catalogada como **LAP4** en el documento [Analysis of Focus Measure Operators in Shape-From-Focus](https://www.researchgate.net/publication/234073157_Analysis_of_focus_measure_operators_in_shape-from-focus), y utiliza la varianza del Laplaciano para hacer el cómputo.

### Archivos

- La notebook `vision_tp2.ipynb` posee todo el contenido, usando `matplotlib.pyplot.imshow` para mostrar las imágenes.
