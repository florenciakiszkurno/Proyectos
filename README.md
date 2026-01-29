# Proyectos

## Clasificacion_expresiones_genomicas
Proyecto grupal universitario cuyo objetivo fue seleccionar el mejor modelo de machine learning (sin redes neuronales) para la predicción de tumores malignos. El modelo se entrenó con un dataset que se nos fue dado y evaluado usando un esquema de held-out para estimar su performance en un dataset desconocido. El script incluye el código para generar las predicciones, aunque los targets reales no están disponibles. La performance estimada por mi grupo fue 0.7819 y la performance real obtenida fue 0.8915.

## Restauracion_puntualizacion_y_capitalizacion
Proyecto universitario enfocado en transformar texto crudo (minúsculas, sin signos) en texto gramaticalmente correcto. Se desarrolló un pipeline en PyTorch que consume embeddings contextuales de BERT para alimentar redes LSTM y Bi-LSTM, capturando dependencias sintácticas complejas. Para evaluar el rendimiento, se compararon estos modelos frente a un enfoque clásico de Random Forest basado en feature engineering específico. El entrenamiento se realizó utilizando datasets de Wikipedia (Hugging Face) preprocesados y adaptados para la tarea de clasificación a nivel de token.
