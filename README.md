# Aplicación de Inteligencia Artificial para la segmentación de imágenes médicas de la columna vertebral  
*Artificial Intelligence Application for medical image segmentation of the spine*
## Descripción
Este repositorio contiene el código desarrollado para mi Trabajo de Fin de Grado en Ingeniería Informática, centrado en la segmentación automática de la columna vertebral a partir de imágenes médicas, principalmente radiografías laterales. 

El proyecto implementa un sistema completo basado en **modelos de segmentación tipo U-Net con encoder ResNet34**, incluyendo:
- Preprocesado y normalización de imágenes.
- Entrenamiento de modelos de segmentación.
- Posprocesado para limpiar y separar vértebras.
- Cálculo de **métricas clínicas angulares y traslacionales** relevantes para el análisis y apoyo al diagnóstico médico.

El objetivo principal es explorar el uso de **deep learning** para mejorar el análisis de imágenes médicas de columna vertebral.

## Tecnologías utilizadas
- Python  
- PyTorch  
- FastAI  
- OpenCV  
- NumPy / Pandas  
- Matplotlib / Seaborn  

## Estructura del repositorio
- `notebooks/`
  - `1_preprocesar.ipynb` - Conversión, normalización y preparación de imágenes.  
  - `2_entrenar_modelos.ipynb` - Entrenamiento de modelos U-Net con encoder ResNet34.  
  - `3_postprocesado.ipynb` - Limpieza y validación de las máscaras segmentadas.  
  - `4_metricas_clinicas.ipynb` - Cálculo de métricas clínicas a partir de las segmentaciones finales.
- `docs/`
  - `informe_tfg.pdf` - Informe completo del proyecto
- `README.md` - Este archivo.

## Datos
Por motivos de privacidad y licencia, las imágenes utilizadas en el proyecto **no se incluyen** en este repositorio.  
Las instrucciones para estructurar los datos pueden encontrarse dentro de los notebooks correspondientes.

## Resultados
Las salidas de las celdas han sido eliminadas para reducir el tamaño de los archivos.  
Los resultados completos (gráficas, segmentaciones y métricas) están documentados en la memoria del TFG.

## Autoría
**Tania Évora Vargas Martínez**  
Grado en Ingeniería Informática  
Universidad de La Laguna (ULL)  
2025

### Tutor académico
**Rafael Arnay del Arco**  
Profesor Titular de Universidad  
Departamento de Ingeniería Informática y Sistemas  
Universidad de La Laguna

## Nota sobre este repositorio
El repositorio original del proyecto estaba alojado en mi cuenta institucional de la universidad.  
Esta es la **versión actualizada y mantenida** del código, migrada a mi cuenta profesional de GitHub.
