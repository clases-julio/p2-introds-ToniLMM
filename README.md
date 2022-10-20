# P2-IntroDS

##### Fecha: 20/10/2022
##### Autor: Marí Marí, Toni Lázaro
##### Objetivo: El principal objetivo de esta práctica es saber como funciona y un diagrama de clases y crear uno para la empresa que nos indica el enunciado.

## Introducción
Esta práctica es una de las tantas que vamos a hacer para realizar el trabajo que nos ha pedido la empresa. Este trabajo consiste en desarrollar un sistema software para dar soporte a una infraestructura de sensores para controlar y recoger datos de un huerto.

## Ejercicio
Este diagrama de clases ha sido diseñado para dar solución al trabajo e implementarlo utilizando programación orientada a objetos (POO). Este boceto esta hecho sin saber prácticamente nada ya que me pensaba que en esta práctica también se pedían los atributos y los métodos de las clases. Sin embargo al recibir hoy la práctica 3 nos hemos dado cuenta de que el objetivo principal era solo crear las clases de dicho diagrama. Como he dicho anteriormente este es un boceto hecho sin conocer muy bien la relación de flechas, como se escriben los atributos y los métodos de las clases etc. por lo tanto en la práctica 3 este diagrama de clases estará sujeto a muchos cambios.

![p2](https://user-images.githubusercontent.com/92941378/197017890-090ae839-c454-4523-9955-b12d3b845e53.jpg)


Este diagrama de clases esta hecho de forma fácil e intuitiva pero repito que sufrirá cambios para ser mejorado con la información de la clase de hoy. Para empezar hemos creado la clase server donde se almacenarán todos los datos de dicha empresa, ya sean los datos captados por los sensores y camaras, además de los datos de los empleados. Al server accederán prácticamente todas las clases debido a que es el núcleo que contiene toda la información. Luego podemos observar la clase user que comprobará si el usuario es un user (trabajador) o un administrador (admin), en este último caso el admin puede acceder al server o base de datos y será el único que lo podrá modificar. Para saber que empleado ha accedido he creado la clase Login que comprobará el número de empleado y su NIF y para comprobarlo esta clase accederá a la base de datos. Como interfaz y menú de la empresa tenemos la clase dashboard que nos mostrará diferentes opciones, información sobre los sensores y nos permitirá salir de este también. Esta empresa nos ha pedido una alarma por lo que hemos creado la clase alarma además de un interruptor para ella ya que estaba especificado por la empresa. También hemos implementado una clase para el teclado y otra para la pantalla ya que nos harán falta para realizar el login, además de una clase microfono que nos permitira interaccionar con el dashboard. Por último tenemos una clase para cada sensor, también he creado una clase para cada tipo de camara, sin embargo he decidido divider los sensores y las camaras en 2 ya que los sensores heredarán las características de la clase 'sensors' mientras las camaras heredarán las características de la clase 'cameras'.


# Conclusión

Esto es un boceto del diagrama de clases ya que para la práctica 3 estará todo mejor explicado, las flechas estarán puestas de manera correcta y agregaré atributos y metodos a varias clases. 
