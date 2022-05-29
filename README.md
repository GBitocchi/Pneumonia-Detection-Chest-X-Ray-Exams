# Universidad-Austral-Tesis-Maestria-Chest-X-Ray-Recognition
 * Alumno: Gustavo Ayrton Bitocchi
 * Director: Diego Alexis Evin
 * Universidad Austral Cohorte 2020/21
 * Trabajo Final de Maestría

# Requisitos
Conjunto de datos de entrenamiento y prueba.

## Entorno de ejecución
Se utilizo el framework de pytorch para la creacion y el entrenamiento de redes neuronales con el siguiente entorno de trabajo:
  * Python version 3.10.4
  * Pytorch version 1.11.0
  * CUDA version 11.6.2
  * Ubuntu 20.04 LTS 

## Utilización

### El directorio Arquitectura-CNN-Autogenerada-CGP contiene los siguientes 3 archivos:

  * Generacion_Arquitectura_CNN_CGP_AWS_SageMaker.ipynb : Notebook que lleva a cabo un proceso CGP para la creacion automatica de una arquitectura CNN.
  * Entrenamiento_Arquitectura_Generada_CNN_CGP_AWS_SageMaker.ipynb : Notebook que entrena la arquitectura CNN autogenerada.
  * Evaluacion_Arquitectura_CNN_CGP.ipynb : Notebook que evalua la arquitectura CNN autogenerada.
  
### El directorio Benchmark-ResNet50 contiene el siguiente archivo:

  * Benchmark_ResNet50_AWS_SageMaker.ipynb: Notebook que realiza EDA sobre conjunto de datos y entrenamiento de modelo benchmark ResNet50
  
### El directorio Grad-CAM contiene el siguiente archivo:

  * Grad_CAM_Modelo_ResNet50.ipynb: Notebook que toma una imagen de prueba y genera su heatmap.
