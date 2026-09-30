# TP1: Perceptrón simple

**Tecnicatura en Inteligencia Artificial**

 - Universidad Nacional de Hurlingham
 - Docente: Emiliano Churruca

## Ejercicio 1

Implemente el algoritmo de perceptrón simple con función de activación escalón y utilícelo para aprender los siguientes problemas:

- Función lógica **'Y'** con entradas `x = {{−1, 1}, {1, −1}, {−1, −1}, {1, 1}}` y salida esperada `y = {−1, −1, −1, 1}`.
- Función lógica **'O exclusivo'** con entradas `x = {{−1, 1}, {1, −1}, {−1, −1}, {1, 1}}` y salida esperada `y = {1, 1, −1, −1}`.

¿Qué puede decir acerca de los problemas que puede resolver el perceptrón simple escalón en relación a la resolución de los problemas que se le pidió que haga que el perceptrón aprenda?

## Ejercicio 2

Implemente el algoritmo del perceptrón simple lineal y perceptrón simple no lineal y utilícelos para aprender el problema especificado en los archivos `TP1-ej2-Conjuntoentrenamiento.txt` y `TP1-ej2-Salida-deseada.txt`.

- Evalúe la capacidad del perceptrón simple lineal y perceptrón simple no lineal para aprender la función cuyas muestras están presentes en los archivos indicados.
- Evalúe la capacidad de generalización del perceptrón simple no lineal utilizando, de los datos provistos, un subconjunto de ellos para entrenar y otro subconjunto para testear.
- ¿Cómo podría escoger el mejor conjunto de entrenamiento?
- ¿Cómo podría evaluar la máxima capacidad de generalización del perceptrón para este conjunto de datos?


---

# TP2: Perceptrón multicapa

**Fundamentos de Redes Neuronales**
Tecnicatura en Inteligencia Artificial — Universidad Nacional de Hurlingham
Docente: Emiliano Churruca

Implemente un perceptrón multicapa y utilícelo para aprender los siguientes problemas:

## Ejercicio 1

Función lógica **'O exclusivo'** con entradas `x = {{-1, 1}, {1, -1}, {-1, -1}, {1, 1}}` y salida esperada `y = {1, 1, -1, -1}`.

## Ejercicio 2

Discriminar si un número es **par**, con entradas dadas por el conjunto de números decimales del 0 al 9 (usar archivo `TP2-ej3-mapa-de-pixeles-digitos-decimales.txt`) representados por imágenes de 5 x 7 píxeles.

Entrene con un subconjunto de los dígitos y utilice el resto para testear a la red. ¿Qué podría decir acerca de la capacidad para generalizar de la red?

## Ejercicio 3

Construya un perceptrón multicapa con la misma entrada usada en 2) pero con **10 unidades de salida**, de modo que cada salida represente a un dígito (por ejemplo, si se le presenta a la red la imagen del 7, el estado de la unidad de salida número 7 esté en 1 y las restantes en 0).

Una vez que la red haya aprendido, use patrones de entrada correspondientes a los dígitos de entrenamiento pero con sus píxeles afectados por ruido (por ejemplo, con probabilidad 0,02, intercambie el valor de los bits en la imagen del dígito) y evalúe los resultados.
