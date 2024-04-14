# Bienvenido a mi tp0!

El enunciado completo del tp0 es el siguiente:

> https://aulasvirtuales.frba.utn.edu.ar/mod/assign/view.php?id=1563183
*Es necesario estar matriculado en el aula virtual "2024 - Sintaxis y Semántica de los Lenguajes K2152" de la UTN FRBA para acceder al link.*


------------


#### Objetivos del tp0:

Básicamente, los objetivos del tp0 son:

- Demostrar capacidad para editar, compilar, y ejecutar programas C mediante
el desarrollo de un programa simple.
- Tener un primer contacto con las herramientas necesarias para abordar la
resolución de los trabajos posteriores.


------------

### Paso a paso de cómo resolví el tp0

En esta sección explico brevemente la forma en la que resolví el tp0.

1. Me descargué el compilador gcc siguiendo el siguiente tutorial:
https://code.visualstudio.com/docs/cpp/config-mingw

2. Creé un programa sencillo para saber qué estándar de C usa mi gcc por defecto. Este programa simplemente usa la macro __\_\_STDC\_VERSION\_\___ para determinar el estándar de C con el que compila por defecto si no se lo especifico manualmente. Por defecto, la versión de mi compilador usa el estándar C18. Así que, por pereza de no especificar manualmente el estándar de C que quiero usar al momento de compilar, este tp fue compilado usando el estándar C18 (mi predeterminado.

3. Creé el programa __hello.c__; lo compilé mediante consola; ejecuté el ejecutable que fue creado; verifiqué que la salida sea la esperada; y volví a ejecutarlo pero redirigiendo la salida al archivo output.txt.

4. Escribí este README.md

5. Comiteé los cambios y los pusheé a este repositorio.