# list_factorial - gmacias-
El objetivo de este proyecto es simple: crear una función que muestre todas las posibilidades de un factorial.
### Indice
* [Que es list_factorial?](#que-es-list_factorial)
* [Que utilizamos?](#que-utilizamos)
* [Como funciona?](#como-funciona)
* [Como utilizamos la función?](#como-utilizamos-la-función)

### Que es list_factorial?
list_factorial es un projecto donde una función muestra todas las posibilidades de un factorial.

<b>El prototipo de la función debe ser la siguiente:</b>

```C
void factorial(int n);
```

### Que utilizamos?
En nuestro list_factorial utilizamos:

| Función  | Descripción														 			|
|-------|-----------------------------------------------------------------------------------|
| malloc | Solicitar un bloque de memoria del tamaño suministrado como parámetro.     													|
| free | Desasigna un bloque de memoria que se había asignado previamente mediante una llamada. 											|
| print |  mostrar por pantalla el resultado               									|


### Como funciona?

A la función le mandaremos el numero el cual querremos que nos de la lista:  

	3!  ->	6 posibilidades

Cada vez que llamemos a la función imprimirá la lista completa y **ordenada**, aqui el ejemplo:
```C
...
factorial(3);
...
```
Output:

	1, 2, 3,  
 	1, 3, 2,  
  	2, 3, 1,  
 	2, 1, 3,  
  	3, 1, 2,  
 	3, 2, 1,  
  	proves: 6

El resultado mostrará la lista y todas las posibilades impresas.

### Como utilizamos la función?

Para utilizarlo primero debes saber la ruta de la funcion y utilizar el archivo .h de esta función. Luego añadirlo en el
encabezado de tu programa:

```C
#include "./<carpeta_de_list_factorial>/list_factorial.h"
```

y eso ya estaría listo para usar!

# Quizás pueda interesarte!

### - Para ver mi progresion en 42 🌠
[AQUÍ](https://github.com/gjmacias/42BCN)

### - Mi perfil de 42 👾
[AQUÍ](https://profile.intra.42.fr/users/gmacias-)

### - Mis proyectos personales 🧐
[AQUÍ🗒️](https://github.com/gjmacias/autoproyectos)

# Contacto 📥

◦ Email: gmacias-@student.42barcelona.com

[1]: https://www.42barcelona.com/ "42 BCN"
