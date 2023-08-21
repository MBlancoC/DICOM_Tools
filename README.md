# Repositorio de Procesamiento de Imágenes DICOM

Este repositorio contiene una serie de utilidades para procesar imágenes DICOM y obtener imágenes DTI (Diffusion Tensor Imaging) y T1 a partir de una carpeta de imágenes DICOM. Además, se proporciona un archivo para realizar la renderización 3D de las imágenes procesadas.


## Contenido

- [`All_Dicom_images.ipynb`](All_Dicom_images.ipynb): Jupyter Notebook que realiza el procesamiento de imágenes DICOM. Utiliza la información de la cabecera DICOM para identificar y extraer imágenes DTI y T1 de la carpeta de imágenes DICOM proporcionada.

- [`render_image.ipynb`](render_image.ipynb): Jupyter Notebook que genera una renderización 3D a partir de un conjunto de imágenes en formato `.tiff`. El resultado final muestra una visualización 3D de la vasculatura formada a partir de las imágenes.