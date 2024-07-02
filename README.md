# TFG_IsabelGonzalezSanchez
Contenido TFG Isabel González Sánchez

En este repositorio se podrá encontrar dos archivos de código realizado en Python:

- manejarDatos.ipynb: este código se encarga de filtrar los datos de los archivos CSV obtenidos de la aplicación Consensys, eliminando los datos no deseados recolectados por la pulsera inteligente Shimmer como son valores "NaN". Hay que indicarle la ruta y el nombre del archivo que queremos filtrar y permite escribir la ruta que se quiera para guardar el nuevo archivo.
Además, también va a realizar las medias de las columnas con la condición de que tengan el mismo timestamp interno de Shimmer. De esta forma se va a rebajar la cantidad de datos registrados por Shimmer, siendo más fácil el análisis de éstos por los usuarios.

- graficasDatos.ipynb: este código permite generar gráficas de los datos de los archivos CSV. El usuario debe indicar la ruta y el nombre del archivo que deesea leer para, a continuación, indicar de qué columna quiere que se generen las gráfica.
Se puede, o bien, hacer una sola gráfica de las tres columnas relacionadas con los datos registrado de movimientos (ACCEL_LN, GYRO_MPU9150, ACCEL_LSM303DLHC, MAG_LSM303DLHC) y en este caso se mostrarían los ejes "x", "y" y "z" o una gráfica de una de las otras columnas de datos.


