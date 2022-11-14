# Titulo: Modelo de regresion lineal
* Utilizar modelos de regresi´on para la estimaci´on de datos.
* Diseñar una estrategia que garantice la correcta seleccion del modelo de regresion, teniendo como
referencia el posible underfitting/overfitting sobre los datos de entrenamiento.

## Tabla de Contenidos
* [Descripción](#descripción)
* [Datos](#datos)
* [Requerimientos](#requerimientos)
* [Soporte](#Support)

## Descripción

Regresion Lineal:

 El archivo “data.npy” es un diccionario, el cual contiene dos matrices: training set y testing set. El conjunto de entrenamiento, “training set”, esta compuesto por 500 observaciones referentes al número de Scooters eléctricos alquilados en una determinada ciudad.

El conteo total de alquileres diarios corresponde a “Count”, mientras que “Casual” y “Registered”
indican si los alquileres corresponden a usuarios casuales o registrados, respectivamente.

a.) Para un d´ıa festivo (Holiday = 1), realice una regresi´on polinomial de “Casual” en funcion de “Temperature”; es decir, x = “Temperature” y y = “Casual”. Dise˜ne una estrategia para determinar el orden del polinomio que realiza la mejor estimacion.
b.) Con base en el mejor modelo obtenido seg´un su criterio, realice las predicciones de y sobre el conjunto de prueba “testing set”*.

## datos:

Dentro del folder "data\raw" se encuentra el archivo data.npy. Este archivo contiene:

500 observaciones referentes al número de Scooters eléctricos alquilados en una determinada ciudad.

## Requerimientos
Se Ejecuto en un ambiente local los modelos regresion lineal
No requiere GPU para realizar pruebas.

## Support
Johan Montano - jmrmontano@hotmail.com
