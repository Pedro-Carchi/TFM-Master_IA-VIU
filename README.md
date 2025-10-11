# TFM-Master_IA-VIU
Este repositorio contiene los códigos empleados para la realización del TFM del Máster en Inteligencia Artificial de la VIU. 

- El notebook descarga_datasets.ipynb permite descargar los datos de Yahoo Finance. Se almacenan en la carpeta externa "datasets".
- El notebook preprocesamiento_datos.ipynb trabaja con los datasets descargados. Se crean los features y se guardan en una carpeta externa "datasets_features" para poder acceder a ellos desde otros notebooks.
- Los notebooks llamados hiperparametros_(nombre modelo).ipynb permiten hace búsqueda de hiperparámetros.
- Los notebooks llamados modelo_(nombre modelo).ipynb construyen los modelos de aprendizaje usando como hiperparámetros los obtenidos por los notebooks anteriores. Se hacen las predicciones y se calculan las métricas. Se guardan, para cada acción y cada bloque, los resultados correspondientes en las carpetas "resultados_metricas" y "resultados_predicciones".
- El notebook graficos.ipynb permite hacer las gráficas de las predicciones que luego irán en la memoria. Se almacenan el la carpeta "imagenes". 
