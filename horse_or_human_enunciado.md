Para este apartado se propone usar el dataset de Kaggle de https://www.kaggle.com/sanikamal/horses-or-humans-dataset , que contiene imágenes de caballos y de seres humanos. Con ello, a modo similar al ejercicio de ejemplo, se pide construir una CNN para clasificación que use esos datos usando como arquitectura de referencia LeNet-5.

Este dataset no es necesario separarlo en train/test ya que ya viene separado desde el origen. Se debe usar la carpeta de ‘train’ para entrenar y validar el modelo, y la de ‘validate’ para hacer la evaluación.

El modelo será un modelo de clasificación binaria, con lo que esto se debe tener en cuenta en la especificación de ciertos parámetros (función de salida, dimensión de la salida…). Para ello, se puede usar el código de los apuntes como referencia, si se quiere, y modificar las partes relevantes para este problema.

Como parte totalmente opcional, si se quiere, se puede probar con otras de las arquitecturas mencionadas previamente para comparar los resultados.