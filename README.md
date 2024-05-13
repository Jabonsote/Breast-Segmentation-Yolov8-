# Breast-Segmentation-Yolov8

Este repositorio contiene una implementación de segmentación de mamas utilizando YOLOv8, una versión mejorada del popular modelo YOLO (You Only Look Once) para detección de objetos en imágenes. La segmentación de mamas es una tarea crucial en aplicaciones médicas como el diagnóstico de cáncer de mama a partir de imágenes de mamografías.

## Descripción del Proyecto

En este proyecto, se ha entrenado un modelo YOLOv8 utilizando un conjunto de datos específico para la segmentación de mamas. El modelo es capaz de identificar y segmentar con precisión las regiones correspondientes a las mamas en imágenes médicas.

## Contenido

- **notebooks/**: Esta carpeta contiene un Google Colab Notebook que detalla el proceso de entrenamiento del modelo YOLOv8 y su aplicación en la segmentación de mamas.
- **models/**: Contiene los archivos de configuración y pesos pre-entrenados del modelo YOLOv8.
- **results/**: En esta carpeta se almacenan los resultados de la segmentación obtenidos por el modelo.
- **demo/**: Aquí se encuentra una demo desplegada del proyecto para probar la segmentación en imágenes de muestra : [DEMO](https://universe.roboflow.com/uabc-auri0/breast-segmentation-dxcby/model/3)

![Demostración de segmentación](images/segmentation_demo.png)


## Uso

Para utilizar este proyecto, sigue estos pasos:

1. Clona este repositorio en tu máquina local o haz una copia del cuaderno.
2. Accede al notebook en la carpeta `notebooks/` y sigue las instrucciones para entrenar el modelo o realizar la segmentación en imágenes de prueba.
3. Explora los resultados en la carpeta `results/` y ajusta los parámetros según sea necesario.


## Datos

Los datos utilizados en este proyecto se encuentran disponibles en el siguiente enlace: [Breast Segmentation Dataset](https://universe.roboflow.com/uabc-auri0/breast-segmentation-dxcby/dataset/3)

![DATOS](images/segmentation_demo.png)

# Resultados

![Metricas del entrenamiento](images/segmentation_demo.png)



## Contribución

¡Las contribuciones son bienvenidas! Si tienes alguna idea de mejora o detectas algún problema, no dudes en abrir un issue o enviar un pull request.

## Referencias

- [YOLOv8: An Improved Version of You Only Look Once]([link_to_paper](https://github.com/ultralytics/ultralytics))

## Licencia

Este proyecto está bajo la Licencia MIT. Para más detalles, consulta el archivo `LICENSE`.
