    Universidad Rafael Landívar
    Facultad de Ingeniería
    Ingeniería en Informática y Sistemas
    Álgebra Lineal
    Ing. Munuel Ríos

                                                              Proyecto final
                                                              Álgebra Lineal 
                                                                   2017

                                                                                                                 Lester García 1003115
                                                                                                                 
                                                      Guatemala, 20 de julio de 2017
                                                      
                                                      

¿En que consiste la convolución y cómo puede ser calculada?

Una convolución es una función, que de forma lineal y continua, transforma una señal de entrada en una nueva señal de salida.
Dicha función se expresa por el símbolo *.

En palabras más simples, s epodría decir que una convolución es un filtro con un propósito aplicado a imagenes y/o fotos.

Una imagen está conformada por pixeles, y se sabe que estos forman una matriz numérica de valores, y ahí es donde el funcionamiento
de una convolución entra en funcionamiento, ya que una una convolución es una matriz aplicada a una imagen de ciertas dimensiones con
operaciones matemáticas sobre valores enteros.

Funciona generalmente determinando el valor numérico de un pixel central de la matriz de pixeles numéricos de la imagen por medio de la suma
de los pixeles a los alrededores de dicho pixel central.

Como resultado de salida, se obtiene una imagen totalmente nueva con el filtro ya aplicado.


¿Qué es el kernel de un filtro y para que se utiliza?

El kernel de un filtro, en palabras simples, es una matriz de menor tamaño utilizada en la convolución de imágenes y se utiliza
para dar los efectos deseados en la imagen en la cual se está trabajando, así como suavizar, acentuar, intensificar y mejorar; todo
eso a nivel de la matriz de pixeles de valores numéricos de la imagen trabajada.


¿En qué consiste un filtro Gaussiano?

En la electrónica y sistemas, un filtro gaussiano es un filtro cuya respuesta de impulso es una función gaussiana 
(o una aproximación a ella). Los filtros gaussianos tienen las propiedades de no tener sobrepaso a una entrada de función escalonada 
minimizando al mismo tiempo el tiempo de subida y bajada. Este comportamiento está estrechamente relacionado con el hecho de que el 
filtro gaussiano tiene el retardo de grupo mínimo posible.


¿En qué consiste el Filtro Sobel? ¿para qué sirve?

El filtro Sobel detecta los bordes horizontales y verticales separadamente sobre una imagen en escala de grises. Las imágenes en 
color se convierten en RGB en niveles de grises. El resultado es una imagen transparente con líneas negras y algunos restos de color.

Describa el algoritmo de detección de bordes Canny

El algoritmo de Canny, mejor conocido como el algoritmo de detección de bordes de canny, como su nombre lo indica, en base a los 
bordes encontrados en una imagen, y luego, realiza una serie de pasos que llevarán a un resultado nuevo en base a sistemas lineales
continuos.

Se puede decir que dicho algoritmo se divide en dos etapas:
!) Reducción de ruido
2) Encontrar la intensidad del gradiente de la imagen
