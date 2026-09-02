# Laboratorio1ED
Este repositorio presenta la solución al problema planteado en clase para el laboratorio #1 de Estructuras de Datos y Laboratorio.

## Archivos del Repositorio

### `MatrizLab.py`
- Se genera la matriz de `100.000 × 100.000`.
- Se generan los datos por bloques de 1.000 filas.
- Se convierten los valores `0` y `1` a bytes para poder escribirlos en el archivo.
- Se agrega el carácter `|` al final de cada fila.
- Se guarda la matriz completa en `matriz.txt`.
- Se guarda la primera fila de la matriz en `primera_fila.txt`.
- Se verifica que la matriz sea válida (tamaño y elementos).
- Se muestra información sobre el tiempo que tardó el proceso y el tamaño de los archivos generados.

Se decidió manejar bloques de 1.000 filas x 100.001 columnas porque la matriz en total pesa aproximadamente 10 GB (9.31 GB), de manera que, realizándolo de esta forma, se controla mejor el uso de memoria. Por otra parte, se agrega una columna extra, ya que va a ser ocupada por un carácter que ayudará a indicar el fin de cada fila de la matriz.

Los archivos `matriz.txt` y `primera_fila.txt` no se incluyen en el repositorio, ya que son generados automáticamente al ejecutar el programa.

## Estudiante: Valentina Flórez Acosta
