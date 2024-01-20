# PRACTICA-N-7-NodeRed
Este repositorio contiene el flow 1 en la cual se utilizo NodeRed

## Introducción

El flow 1 representa el primer ejercicio a realizar con NodeRed. Este ejercicio consiste únicamente en conectar un nodo Slide con un nodo gauge y chart. Esta acción permite demostrar el uso de la pestaña Debug.

## Material Necesario

Para realizar este flow necesitas lo siguiente

- [Node.js](hhttps://nodejs.org/en)


## Instrucciones

### Requisitos previos

Para que este flow funcione, debes cumplir con los siguientes requisitos previos
1. Tener instalado Node.js (version 20.11.0 LTS).

### Instrucciones de preparación del entorno

Para ejecutar este flow, es necesario lo siguiente
1. Arrancar el contenedor de NodeRed en **cmd** con el comando
        
        node-red

2. Dirigirse a [localhost:1880](localhost:1880)


Para la realizacion de este primer flow necesitamos instalar un paquete de **Dashboard** de la siguiente manera 
1. Abrimos la pestaña de opciones y elegimos  **Manage palette**
![](https://github.com/YasminZagal/PRACTICA-N-7-NodeRed/blob/main/manage%20palet.png)

2. Seleccionamos --> Install y buscamos **node-red-dashboard**
![](https://github.com/YasminZagal/PRACTICA-N-7-NodeRed/blob/main/install.png)

3. Y para terminar le colocamos install

   
### Instrucciones de operación
1. En el lado izquierdo del panel se encuentran los nodos, en nuestro caso solo utilizaremos un Slider, un Gauge y un Chart
![](https://github.com/YasminZagal/PRACTICA-N-7-NodeRed/blob/main/herramientas.png)
![](https://github.com/YasminZagal/PRACTICA-N-7-NodeRed/blob/main/nodos%20a%20utilizar.png)

2.Uniremo nuestros nodos 
![](https://github.com/YasminZagal/PRACTICA-N-7-NodeRed/blob/main/resultado%201.png)

3.Modificaremos los nombres de nuestros nodos y valores en nuestro caso se coloco el nombre de **humedad**
![](https://github.com/YasminZagal/PRACTICA-N-7-NodeRed/blob/main/slider.png)
![](https://github.com/YasminZagal/PRACTICA-N-7-NodeRed/blob/main/gauge.png)
![](https://github.com/YasminZagal/PRACTICA-N-7-NodeRed/blob/main/chart.png)

## Resultados

A continuación se puede observar una vista previa del resultado del flow1.
![](https://github.com/YasminZagal/PRACTICA-N-7-NodeRed/blob/main/RESHUM1.png)
![](https://github.com/YasminZagal/PRACTICA-N-7-NodeRed/blob/main/RESHUM2.png)
![](https://github.com/YasminZagal/PRACTICA-N-7-NodeRed/blob/main/RESHUM3.png)




