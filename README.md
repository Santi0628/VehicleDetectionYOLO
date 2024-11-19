VehicleDetectionYOLO
Este repositorio contiene un proyecto para la detección y clasificación de vehículos utilizando YOLOv8, optimizado para identificar cinco clases: 
Ambulancia, Autobús, Coche, Motocicleta y Camión. El modelo fue entrenado con datos de Kaggle y evaluado con imágenes y videos de prueba, logrando resultados prometedores.

Contenido del Proyecto

Preparación de Datos:
Descarga de dataset desde Kaggle (Vehicle Detection Dataset).
Análisis y balanceo de clases.
Aumento de datos mediante preprocesamiento y técnicas de augmentación.

Modelado:
Modelo YOLOv8n preentrenado como base.
Configuración de entrenamiento con early stopping.
Métricas clave: mAP50 general de 60.7% con un rendimiento sobresaliente en clases como Ambulancia.

Evaluación:
Visualización de predicciones en imágenes de prueba y videos.
Matriz de confusión para análisis detallado de clasificaciones correctas e incorrectas.
Métricas como precisión (0.636) y recall (0.507).

Visualizaciones:
Función de pérdida y precisión a lo largo de las épocas.
Resultados destacados en video y gráficos de rendimiento.

Requisitos
Python 3.8+
Bibliotecas:
ultralytics, torch
opencv-python-headless
pandas, matplotlib, seaborn, plotly
wandb, kagglehub
