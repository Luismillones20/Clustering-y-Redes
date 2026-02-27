# 📊 Pipeline de Clustering y Análisis de Datos

Un pipeline de aprendizaje automático no supervisado diseñado para la segmentación de datos de usuarios y el descubrimiento de patrones ocultos utilizando el dataset **MovieLens 100k**. 

Este proyecto implementa, evalúa y compara modelos de clustering para agrupar usuarios en función de sus preferencias y comportamientos, estableciendo una base analítica para sistemas de recomendación.

## 🚀 Tecnologías y Herramientas
* **Lenguaje:** Python 3.x
* **Machine Learning:** Scikit-Learn
* **Manipulación de Datos:** Pandas, NumPy
* **Visualización:** Matplotlib, Seaborn

## ⚙️ Metodología y Arquitectura del Modelo

1. **Preprocesamiento de Datos:** Limpieza, normalización y transformación del dataset MovieLens 100k.
2. **Determinación de Hiperparámetros:** * Uso de la **Curva Elbow (Método del Codo)** para estimar el número inicial de clusters ($k$).
   * Validación técnica y ajuste fino utilizando el **Coeficiente de Silhouette (Silhouette Score)** para maximizar la cohesión intra-cluster y la separación inter-cluster.
3. **Modelado:** * Entrenamiento de modelos **K-Means** para clustering particional.
   * Implementación de **Mean Shift** para el descubrimiento automático de densidades sin necesidad de predefinir el número de clusters.
4. **Análisis de Resultados:** Visualización en 2D/3D (mediante reducción de dimensionalidad como PCA) y conclusiones sobre los perfiles de usuario detectados.

