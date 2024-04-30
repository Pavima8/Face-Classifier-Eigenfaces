# Clasificación de Caras utilizando Eigenfaces y PCA/KPCA
Este proyecto se centra en la clasificación de caras utilizando el concepto de Eigenfaces junto con el análisis de componentes principales (PCA) y el análisis de componentes principales kernelizados (KPCA). Eigenfaces es una técnica de reconocimiento facial que representa las caras como una combinación lineal de vectores propios (eigenfaces) obtenidos a partir de un conjunto de imágenes de caras.

## Objetivo
El objetivo principal de este proyecto es desarrollar un sistema de clasificación de caras que pueda reconocer y distinguir entre diferentes individuos en imágenes faciales. Esto se logra mediante la extracción de características utilizando PCA y KPCA, seguido de la clasificación utilizando un algoritmo de clasificación adecuado, como máquinas de vectores de soporte (SVM) o k vecinos más cercanos (KNN).

## Tecnologías Utilizadas
Python: Lenguaje de programación principal.
OpenCV: Librería para el procesamiento de imágenes.
scikit-learn: Librería para aprendizaje automático, incluyendo PCA y KPCA.
NumPy: Biblioteca para operaciones matemáticas.
Matplotlib: Biblioteca para visualización de datos.

## Resultados
Tras el entrenamiento y evaluación del modelo de clasificación utilizando PCA y KPCA, se ha observado que ambos métodos logran clasificar con éxito la gran mayoría de las caras en el conjunto de datos de prueba. Tanto PCA como KPCA han demostrado ser eficaces en la extracción de características relevantes de las imágenes faciales, lo que ha permitido que los algoritmos de clasificación logren una alta precisión en la tarea de reconocimiento facial.

Se ha observado que, en general, no hay una diferencia significativa en el rendimiento entre PCA y KPCA para este conjunto de datos específico. Ambos métodos han logrado identificar con precisión a los sujetos en las imágenes faciales, lo que sugiere que la linealidad en la representación de las características no es un factor crítico para esta tarea en particular.

Los resultados obtenidos respaldan la viabilidad y la eficacia del enfoque de Eigenfaces para la clasificación de caras, tanto en su implementación estándar con PCA como en su versión kernelizada con KPCA. Estos resultados son prometedores para su aplicación en sistemas de reconocimiento facial en la vida real, donde la precisión y la robustez son críticas.

## Referencias

- Turk, M. A., & Pentland, A. P. (1991). Eigenfaces for recognition. Journal of cognitive neuroscience, 3(1), 71-86.
- Belhumeur, P. N., Hespanha, J. P., & Kriegman, D. J. (1997). Eigenfaces vs. Fisherfaces: Recognition using class specific linear projection. IEEE transactions on pattern analysis and machine intelligence, 19(7), 711-720.
