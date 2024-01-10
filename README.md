# Metrología Automatiza para elementos mecánicos simples.
Este programa hace parte de mi proyecto individual desarrollado en la Universidad de los Andes. 
Consiste en identificar, caracterizar y analizar un elemento mecánico simple como un eslabón, a través de un análisis de visión por computadora y redes neuronales.

Para ejecutarlo deberá correr el script MainInterfaz.py, y tener instaladas las librerías Tkinder, OpenCv y TensorFlow.
La estructura del programa consta de un archivo MainFunciones.py en el cual se realizan tanto los arreglos morofologicos como el análisis de la figura. 
Dicho script es luego ejecutado en MainInterfaz.py, que luego agrupa la información en una interfaz simple y amigable con el usuario que usa la carpetaa ModosFalla para mostrar la información. 

La carpeta img, son imagenes propuestas para la buena ejecución del programa. No obstante, estas no son las unicas analizables, son solo un grupo de ejemplos del tipo de imagenes a las cuales se hace referencia en el programa.

Los 2 scripts restantes son los que se usaron para la creación de las redes neuronales que luego fueron guardadas con los nombres ModeloMedidasUtiles.h5 y ModeloModosFalla.h5.

Finalmente, para conocer más información al respecto del programa y aclarar dudas, se adjunta el archivo: InformePublico.pdf. El cual explica los objetivos
detrás del proyecto, su funcionamiento, metodología y resultados.
