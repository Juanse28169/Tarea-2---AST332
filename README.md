Tarea 2 - AST332 Clasificación de Machine Learning: "Análisis y Modelado del Bosón de Higgs"

Descripción: Este código busca utilizar Support Vector Machine para clasificar eventos como señales del bosón de Higgs (clase 1) o como ruido de fondo (clase 0), utilizando los conjuntos de datos Higgs_features.csv y Higgs_labels.csv.

El análisis se divide en tres partes. Primero, se realiza una exploración de los datos para entender la distribución de las características, identificar valores anómalos (-999.0) y analizar el balance de clases. Luego, se aplica un preprocesamiento que incluye la limpieza de datos anómalos y la normalización de las características (escalado de 0 a 1). Finalmente, el código entrena un clasificador SVC y evalúa su rendimiento en un conjunto de prueba, reportando la matriz de confusión, la precisión y la sensibilidad (recall).

Contacto: constanza.bustos@usm.cl jgutierrez@usm.cl
