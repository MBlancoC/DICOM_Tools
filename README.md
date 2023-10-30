
# Repositorio de Procesamiento de Imágenes DICOM

Este repositorio contiene una serie de utilidades para procesar imágenes DICOM y obtener imágenes DTI (Diffusion Tensor Imaging) y T1 a partir de una carpeta de imágenes DICOM. Además, se proporciona un archivo para realizar la renderización 3D de las imágenes procesadas.

## Contenido

- [`All_Dicom_images.ipynb`](All_Dicom_images.ipynb): Jupyter Notebook que realiza el procesamiento de imágenes DICOM. Utiliza la información de la cabecera DICOM para identificar y extraer imágenes DTI y T1 de la carpeta de imágenes DICOM proporcionada.

- [`render_image.ipynb`](render_image.ipynb): Jupyter Notebook que genera una renderización 3D a partir de un conjunto de imágenes en formato `.tiff`. El resultado final muestra una visualización 3D de la vasculatura formada a partir de las imágenes.

## Script Python IA

En la carpeta "Script Python IA" se encuentran dos subcarpetas que contienen scripts y módulos para el análisis y procesamiento.

### Autoencoders

Dentro de la carpeta, en el archivo [`Autoencoders.ipynb`](`Script_Python_IA/autoencoders/Autoencoders.ipynb`) se encuentran los análisis realizados con los clasificadores SVM (Support Vector Machines), LDA (Linear Discriminant Analysis), GNB (Gaussian Naive Bayes), Decision Trees, y Regresión Logística.

Además, esta carpeta incluye las definiciones de las clases `myAutoencoder()` y `myAutoencoder_fine_tuning()`, que contienen la arquitectura específica del autoencoder y los métodos de fine-tuning, respectivamente.

### Models

La carpeta "Models" contener los modelos de Autoencoders entrenados.

---
