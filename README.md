# Chinchon-ASCII
Un chincon escrito en C, no terminado, por razones de profundizacion en el lenguaje.
La interfaz está mas o menos terminada, programé un sistema de impresion de cartas flexible que no tiene la necesidad de estancar la vista de las manos y el mazo de cartas en una matriz fija, añadiendo la posibilidad de quitar cartas de la mesa si es necesario, un sistema de controles que usa la barra espaciadora y las flechas direccionales para navegar por los mazos o abrir el menu de seleccion que alterna dependiendo el estado del juego.
Los controles son: Derecha-Izquierda para moverse por la mano, Tecla arriba para arbrir el menu y barra espaciadora para seleccionar carta y luego poder moverlas con las ya mencionadas teclas de direccion.
Un detalle a destacar es el uso de la tan despreciada libreria "conio.h" por su funcion "getch()" que se encarga de obtener el codigo 
de alguna otra tecla presionada sin intervencion de un EOF, lo que permite presionar una tecla y no tener que apretar enter para seguir
la rutina.

No recuerdo muy bien el funcionamiento ni la practica que utilice debido a que desatendi demasiado tiempo el codigo, que forma parte de mis practicas en C, pero tiene preparado las funciones y reglas del juego, solo que falta poder jugar una partida con la Computadora, que es un detalle no menos importante debido a que nunca me puse a planificarlo por que colisiona con el campo de la "inteligencia artificial", espero un dia volver bien instruido en la materia y terminarlo.
