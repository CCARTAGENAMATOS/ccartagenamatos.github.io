---
layout: page
title: Proyectos
permalink: /proyectos/
---

## Proyectos de Inteligencia Artificial

Esta es una muestra de algunos de los proyectos más destacados en los que he trabajado, desarrollando soluciones completas de IA. Desde los datos, modelos y aplicaciones, tengo experiencia con todo el stack.

---

### Detección de Núcleos de Perforación con PyTorch

<p align="center">
  <img src="https://raw.githubusercontent.com/CCARTAGENAMATOS/ccartagenamatos.github.io/refs/heads/master/core.png" alt="Detección de Núcleos de Perforación" width="350">
</p>

*Un modelo de Visión por Computador para la clasificación automática de muestras geológicas de núcleos de perforación, aplicando técnicas de Deep Learning.*

- **Objetivo:** Automatizar la identificación de tipos de roca para acelerar el proceso de análisis geológico y reducir la subjetividad humana.
- **Tecnologías:** Python, PyTorch, Pandas, Scikit-learn, Visión por Computador (CNNs).
- **Mi Contribución:**
    - Implementé un pipeline completo de datos, desde la carga y preprocesamiento de imágenes hasta el entrenamiento del modelo.
    - Entrené una Red Neuronal Convolucional (CNN) para clasificar las imágenes, estableciendo un sólido modelo base de rendimiento.
    - El proyecto demuestra la viabilidad de aplicar IA para optimizar tareas críticas en la exploración minera.

[**Ver el Proyecto en Kaggle**](https://www.kaggle.com/code/cristianminas/mining-core-detection-pytorch-baseline)

---

### Optimización de Procesos Mineros con XGBoost y Explicabilidad (SHAP)

<p align="center">
  <img src="https://raw.githubusercontent.com/CCARTAGENAMATOS/ccartagenamatos.github.io/refs/heads/master/shap.png" alt="Gráfico de Importancia de Variables con SHAP" width="350">
</p>

*Un modelo de machine learning para predecir la pureza del mineral de hierro, con un enfoque en la interpretabilidad del modelo para la toma de decisiones operativas.*

- **Objetivo:** Predecir y controlar la cantidad de impurezas de sílice en un proceso de flotación para mejorar la calidad del producto final y optimizar el uso de reactivos.
- **Tecnologías:** Python, XGBoost, SHAP, Pandas, Scikit-learn.
- **Mi Contribución:**
    - Entrené un modelo robusto de XGBoost para predecir con alta precisión el porcentaje de sílice en el concentrado.
    - Apliqué SHAP para interpretar los resultados del modelo "caja negra", identificando qué variables del proceso tienen el mayor impacto.
    - Este enfoque no solo predice, sino que también **explica**, permitiendo a los ingenieros de planta tomar decisiones informadas para ajustar el proceso.

[**Ver el Proyecto en Kaggle**](https://www.kaggle.com/code/cristianminas/xgboost-mining-process-shap-explainability)

---

### Detección de Equipos Mineros en Tiempo Real con YOLOv5

<p align="center">
  <img src="https://raw.githubusercontent.com/CCARTAGENAMATOS/ccartagenamatos.github.io/refs/heads/master/camiones.png" alt="Detección de equipo minero con YOLOv5" width="350">
</p>

*Un modelo de Detección de Objetos para la identificación y localización de maquinaria pesada en entornos mineros, clave para la seguridad y optimización logística.*

- **Objetivo:** Desarrollar un sistema de visión artificial capaz de detectar y clasificar equipos pesados (camiones, excavadoras) en tiempo real, sentando las bases para aplicaciones de seguridad y monitoreo autónomo.  
- **Tecnologías:** Python, PyTorch, YOLOv5, Roboflow, Visión por Computador.  
- **Mi Contribución:**
    - Entrené un modelo YOLOv5 sobre un dataset personalizado de maquinaria minera, demostrando la capacidad de adaptar soluciones de IA a problemas específicos del sector.  
    - Gestioné el proceso de preparación de datos, incluyendo la anotación (bounding boxes) y el aumento de datos (data augmentation) para mejorar la robustez del modelo.  
    - El resultado es un sistema capaz de operar en tiempo real, fundamental para futuras aplicaciones como la prevención de colisiones y la gestión automatizada de flotas.  

[**Ver el Proyecto en Kaggle**](https://www.kaggle.com/code/cristianminas/mining-equipment-yolov5-train)

---


### Predicción de Fuga de Clientes con Stacking de Modelos

![Arquitectura de Stacking de Modelos]({{ '/assets/img/proyecto_stacking.png' | absolute_url }})
*Un enfoque avanzado de ensemble learning para mejorar la precisión en la predicción de la fuga de clientes (customer churn), un problema crítico para cualquier negocio.*

- **Objetivo:** Construir un modelo de clasificación de alta precisión que identifique a los clientes con mayor probabilidad de abandonar un servicio, permitiendo implementar estrategias de retención proactivas.
- **Tecnologías:** Python, Scikit-learn, XGBoost, Pandas, Ensemble Learning (Stacking).
- **Mi Contribución:**
    - Implementé un modelo de Stacking que combina las predicciones de varios modelos base diversos (ej. Random Forest, Gradient Boosting).
    - Utilicé un meta-modelo (ej. Logistic Regression) que aprende a ponderar las predicciones de los modelos base para generar un pronóstico final más robusto.
    - Esta técnica demostró una mejora en el rendimiento en comparación con los modelos individuales, una práctica común en sistemas de IA de alto rendimiento.

[**Ver el Proyecto en Kaggle**](https://www.kaggle.com/code/cristianminas/2-14-stacking-de-modelos)

---

### Descubrimiento de Yacimientos con IA y Datos Satelitales

![Análisis de Imágenes Satelitales]({{ '/assets/img/proyecto_satelital.png' | absolute_url }})
*Un sistema de inteligencia artificial para el análisis de imágenes satelitales multiespectrales, enfocado en la detección de anomalías geológicas y patrones asociados a yacimientos mineros y arqueológicos.*

- **Objetivo:** Acelerar y reducir el costo de la prospección de nuevos sitios de interés, identificando áreas con alta probabilidad de contener depósitos minerales o restos arqueológicos.
- **Tecnologías:** Python, Teledetección (Remote Sensing), TensorFlow/Keras, Procesamiento de Imágenes, GIS.
- **Mi Contribución:**
    - Desarrollé un modelo de machine learning para analizar y clasificar grandes volúmenes de datos satelitales, identificando firmas espectrales y patrones texturales únicos.
    - Implementé técnicas de segmentación de imágenes para delinear automáticamente las zonas potenciales, optimizando el trabajo de campo de geólogos y arqueólogos.
    - Este proyecto combina mi conocimiento en geociencias con la ciencia de datos para crear una herramienta poderosa de descubrimiento y exploración a gran escala.

<!-- Si tienes un enlace para este proyecto, ponlo aquí. Si no, puedes borrar la siguiente línea -->
[**Más detalles próximamente**](#)

---
