# 📌 Clasificación de Imágenes con Redes Neuronales Convolucionales (CNN)

Este proyecto desarrolla una **Red Neuronal Convolucional (CNN)** para clasificar imágenes en seis categorías:

✅ Buildings (Edificios)  
✅ Forest (Bosque)  
✅ Glacier (Glaciar)  
✅ Mountain (Montaña)  
✅ Sea (Mar)  
✅ Street (Calle)  

El objetivo es mejorar la capacidad de generalización utilizando una arquitectura profunda.

---

## 📌 Tecnologías utilizadas
- Python 3.x
- TensorFlow / Keras
- NumPy, Matplotlib, Scikit-learn
- Google Colab / Jupyter Notebook

---

## 📌 Estructura del Proyecto
1️⃣ **Carga y exploración de datos**  
   - Importación de archivos `.npy`  
   - Análisis de distribución de clases  
   - Visualización de imágenes aleatorias  

2️⃣ **Preprocesamiento de datos**  
   - Normalización de imágenes (`[0,255] → [0,1]`)  
   - Codificación One-Hot de etiquetas  

3️⃣ **Modelado y entrenamiento**  
   - Implementación de redes Fully Connected y Convolucionales  
   - Arquitecturas de 3 a 16 capas (Conv2D + Dense)  
   - Evaluación del rendimiento con métricas de precisión  

4️⃣ **Análisis de errores y predicciones**  
   - Identificación de la clase con más errores  
   - Visualización de imágenes mal clasificadas  

---

## 📌 Cómo ejecutar el proyecto
1. Clonar este repositorio  
   ```bash
   git clone https://github.com/tuusuario/cnn-clasificacion-imagenes.git
   cd cnn-clasificacion-imagenes
