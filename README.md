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
void factorial(int i);
```

### Que utilizamos?
En nuestro list_factorial utilizamos:

| Función  | Descripción														 			|
|-------|-----------------------------------------------------------------------------------|
| malloc | Solicitar un bloque de memoria del tamaño suministrado como parámetro.     													|
| free | Desasigna un bloque de memoria que se había asignado previamente mediante una llamada. 											|
| read |  Lee el contenido del archivo del sistema seleccionado.               									|


### Como funciona?

como he comentado a esta función le envias el file descriptor para leer linea por linea, por ejemplo, si tenemos un archivo
llamado `textoprueba.txt` y tengo el siguiente contenido:  

	linea1  
 	linea2  
  	linea3

Cada vez que llamemos a la función (utilizando el **F**ile**D**escriptor de `textoprueba.txt`)imprimirá una linea:
```C
printf(%s,get_next_line(int fd);
printf(%s,get_next_line(int fd);
printf(%s,get_next_line(int fd);
printf(%s,get_next_line(int fd);
```
Output:

	linea1  //lee la primera linea
	linea2  //lee la segunda linea
	linea3  //lee la tercera linea
	(null)  //devuelve NULL por que ha llegado al final del archivo (EOF)

### Como utilizamos la función?

Para utilizarlo primero debes saber la ruta de la funcion y utilizar el archivo .h de esta función. Luego añadirlo en el
encabezado de tu programa:

```C
#include "./<carpeta_de_get_next_line>/get_next_line.h"
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
