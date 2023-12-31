# Portafolio TC3006C
### Diego Alberto Baños Lopez
### A01275100

# Evidencias

Gracias a la retroalimentación de los profesores a lo largo de esta materia, se ha podido añadir o corregir detalles, haciendo que los entregables aumenten en calidad y, por lo tanto, puedan cumplir de mejor manera con las competencias pedidas a lo largo de esta materia.

## Evidencia 1: Portafolio de análisis

## Modulo 1: Técnicas de procesamiento de datos para el análisis estadístico y para la construcción de modelos

En esta parte del portafolio, se intentará resolver el siguiente problema:
Una empresa automovilística china aspira a entrar en el mercado estadounidense. Desea establecer allí una unidad de fabricación y producir automóviles localmente para competir con sus contrapartes estadounidenses y europeas. Contrataron una empresa de consultoría de automóviles para identificar los principales factores de los que depende el precio de los automóviles, específicamente, en el mercado estadounidense, ya que pueden ser muy diferentes del mercado chino. Esencialmente, la empresa quiere saber:

* ¿Qué variables son significativas para predecir el precio de un automóvil?
* ¿Qué tan bien describen esas variables el precio de un automóvil?
  
El problema nos entrega un archivo CSV llamado "precios_autos" en el cual se nos muestra distintas variables que posiblemente estén relacionadas con el precio. Debemos seleccionar 6 para contestar la primera pregunta. La segunda pregunta se contestará de mejor manera en el portafolio de implementación, que es la continuación de este análisis.

Además, se nos proporciona un diccionario para poder comprender mejor a qué se refieren las variables dentro del problema.

Aquí hacemos una breve descripción de los datos, así como usamos gráficas para poder observar el comportamiento de los mismos. A través del tratamiento de los datos y observando las correlaciones, intentamos averiguar cuál tiene una mayor relación con el precio.

El reporte con mayor detalle para esta primera parte se llama "portafolioModulo1_parte1".

Todo lo relacionado a este análisis se encuentra bajo la carpeta ./Final/Evidencia1_Modulo1.
## Modulo 2: Análisis y Reporte sobre el desempeño del modelo. (Y Análisis del contexto y la normatividad.)

En esta primera evidencia se busca observar el sesgo de un cierto tipo de dataset, observar su varianza, así como el desempeño de diversas métricas y la comparación de dos modelos: regresión lineal y regresión ridge. Se compara con gráficos y con métricas qué tan bien se desempeñan, así como una comparación dentro de los mismos.

Todo lo relacionado a esta evidencia puede encontrarse en la carpeta ./Final/Evidencia1.

Los modelos a evaluar son de tipo regresión.

El reporte es un Notebook en el cual se documenta todo el proceso; ese mismo notebook está en la carpeta previamente mencionada y tiene el nombre de ev1.

Se implementaron como mejora un mayor detalle en el dataset, así como gráficas y estadísticas que ayudan a comprender mejor respecto a su entrega original, así como algunas correcciones en algunas funciones.

Los datos que se usaron para este modelo provienen del siguiente enlace:
https://www.kaggle.com/datasets/vinicius150987/ice-cream-revenue
El dataset es un CSV que consiste, a grandes rasgos, en la relación de la ganancia que tiene una tienda de helados respecto a la temperatura ambiente que hay alrededor de ella.

Cabe resaltar que en esta primera parte se hizo un breve análisis de contexto para el módulo 2, el cual tiene un reporte en PDF en la misma carpeta mencionada anteriormente.
## Evidencia 2: Portafolio de implementación

## Modulo 1: Construcción de un modelo estadístico base

Basándonos en lo que se tenía previamente en la evidencia 1 y recordando las preguntas base anteriores, las cuales eran:

* ¿Qué variables son significativas para predecir el precio de un automóvil?
* ¿Qué tan bien describen esas variables el precio de un automóvil?

Aquí se continúa visualizando los datos atípicos y, en base a lo que se observa en el reporte, se realiza una normalización de los mismos. Una vez hecho ello, se decidió modelar usando regresión lineal múltiple para poder ver qué tan bien las variables seleccionadas pueden predecir el precio del automóvil y contestar la segunda pregunta de mejor forma.

El reporte con mayor detalle para esta parte se llama "portafolioModulo1_parte2".

Todo lo relacionado a este análisis se encuentra bajo la carpeta ./Final/Evidencia2_Modulo1.

## Modulo 2

En la segunda evidencia, en la parte del segundo modulo se tiene dividido en dos partes. A continuación, un breve resumen de las dos partes:

### Modulo 2: Implementación de una técnica de aprendizaje máquina sin el uso de un framework. (Parte 1)

En esta primera parte se observará cómo se implementa la regresión lineal de gradiente descendiente sin el uso de una librería o framework como sería scikit-learn. Además, en el reporte se explica a detalle cómo funciona este y cómo es implementado en un dataset. Este modelo busca hacer predicciones acerca de la ganancia de una tienda de helados respecto al clima; de igual forma, se usan gráficas para poder comprender mejor el modelado.

Se implementó de igual forma la separación de los datos en cuanto al conjunto, algo que no se hizo en la primera entrega. Además, se agregó mayor detalle a la descripción del dataset y correcciones menores a las funciones que se encuentran dentro del reporte. Una corrección muy notable respecto a la retroalimentación es el agregado del README, ya que no contaba con uno y fue agregado después cuando se realizaba la segunda parte de la evidencia 2.

Todo lo relacionado a esta evidencia puede encontrarse en la carpeta ./Final/Evidencia2_1.

El reporte es un Notebook en el cual se documenta todo el proceso; ese mismo notebook está en la carpeta previamente mencionada y tiene el nombre de ev2_1.

Los datos que se usaron para este modelo provienen del siguiente enlace:
https://www.kaggle.com/datasets/vinicius150987/ice-cream-revenue
El dataset es un CSV que consiste, a grandes rasgos, en la relación de la ganancia que tiene una tienda de helados respecto a la temperatura ambiente que hay alrededor de ella.

### Modulo 2: Uso de framework o biblioteca de aprendizaje máquina para la implementación de una solución. (Parte 2)

En esta segunda parte de la evidencia 2, se busca realizar un modelo de regresión lineal usando de apoyo los frameworks, entender cómo trabajan sus hiperparámetros y, en general, comprender estos últimos. Se usan gráficas para apoyo visual.

El único cambio respecto a su retroalimentación es que se añadió una mejor descripción de los datos, ya que fue indicado por el profesor. Más allá de ello, no cambia mucho respecto a su retroalimentación anterior.

Todo lo relacionado a esta evidencia puede encontrarse en la carpeta ./Final/Evidencia2_2.

El reporte es un Notebook en el cual se documenta todo el proceso; ese mismo notebook está en la carpeta previamente mencionada y tiene el nombre de ev2_2.


Los datos que se usaron para este modelo provienen del siguiente enlace:
https://www.kaggle.com/datasets/vinicius150987/ice-cream-revenue
El dataset es un CSV que consiste, a grandes rasgos, en la relación de la ganancia que tiene una tienda de helados respecto a la temperatura ambiente que hay alrededor de ella.

# Momentos de retroalimentación
A lo largo de este curso, se realizaron entregas periódicas, y en este repositorio se dará constancia de cómo fueron entregados para su retroalimentación. Los archivos originales que fueron entregados como retroalimentación estarán guardados bajo la carpeta retro, así como esta sección dará fe de los archivos originales.
## Módulo 2 Implementación de una técnica de aprendizaje máquina sin el uso de un framework.

Todo lo relacionado a esta entrega puede encontrarse en la carpeta de ./Retro/Reto1

El modelo a implementar en este dataset esta basado en regresión lineal, la cual busca medir una relacion entre variables

El desarrollo de este reto (El reporte) esta en el Jupyter Notebook llamado reto1

Los datos que se usaron para este modelo provienen del siguiente link:
https://www.kaggle.com/datasets/vinicius150987/ice-cream-revenue

## Módulo 2 Uso de framework o biblioteca de aprendizaje máquina para la implementación de una solución. 

Todo lo relacionado a esta entrega puede encontrarse en la carpeta de ./Retro/Reto2

El modelo a implementar en este dataser esta basado en regresión lineal, la cual busca medir una relacion entre variables.
En este caso contaremos con el apoyo de frameworks en python para poder hacer dicha solucion

El desarrollo de este reto (El reporte) esta en el Jupyter Notebook llamado reto2

Los datos que se usaron para este modelo provienen del siguiente link:
https://www.kaggle.com/datasets/vinicius150987/ice-cream-revenue

## Módulo 2 Análisis y Reporte sobre el desempeño del modelo. 

Todo lo relacionado a esta entrega puede encontrarse en la carpeta de ./Retro/Reto3

El modelo a evaluar en este dataser esta basado en regresión lineal, la cual busca medir una relacion entre variables.
Aqui ademas se aplicara un metodo de regularización la cual es la la regresión de cresta

En este caso contaremos con el apoyo de frameworks en python para poder hacer dicha solucion

El desarrollo de este reto (El reporte) esta en el Jupyter Notebook llamado reto3

Los datos que se usaron para este modelo provienen del siguiente link:
https://www.kaggle.com/datasets/vinicius150987/ice-cream-revenue