# C Skeleton 

Este es un simple proyecto, con lo bàsico para armar proyectos o practicar en C. Tiene un `Makefile` que permite compilar los archivos en C que estan en la carpeta `src` y los includes que se encuentran en `inc`. Despues se pueden agregar tests en la carpeta con el nombre homònimo, que permite correrlos.

Para compilar basta con hacer:

```bash
make
```

Esto generara el ejecutable en `skeleton` en el root de este proyecto. Para limpiar los archivos objeto y los ejecutables, tendremos que hacer algo como

```bash
make clean
```

En el caso que querramos correr los tests podremos hacer algo como

```bash
make tests
```
