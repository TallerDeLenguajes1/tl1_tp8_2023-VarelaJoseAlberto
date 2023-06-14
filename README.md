# tl1_tp8_2023-VarelaJoseAlberto

# tl1_tp8_2023-VarelaJoseAlberto created by GitHub Classroom

La clase "Path" del espacio de nombres System.IO en C# proporciona métodos y propiedades estáticas para trabajar con rutas de archivos y directorios.

Algunos usos comunes de la clase Path incluyen:

1- Manipulación de rutas de archivos: La clase Path proporciona métodos para combinar rutas, obtener el nombre de archivo, la extensión, el nombre del directorio padre, etc. Puedes usar estos métodos para realizar operaciones en las rutas de archivos, como obtener información específica sobre una ruta
o combinar rutas para formar una nueva ruta.

2- Validación y normalización de rutas: Puedes utilizar los métodos de Path para validar si una ruta es válida y para normalizar rutas eliminando
redundancias y resolviendo referencias relativas (Path.GetFullPath, Path.IsPathRooted, etc.).

3- Extraer información de rutas: Puedes obtener información sobre una ruta de archivo utilizando los métodos de Path. Por ejemplo, puedes obtener
el nombre de archivo sin la extensión (Path.GetFileNameWithoutExtension), obtener solo la extensión (Path.GetExtension),
obtener el nombre del directorio (Path.GetDirectoryName), entre otros.

4- Construcción de rutas de archivos: Path.Combine es un método útil para combinar partes de rutas en una ruta completa. Puedes proporcionar segmentos
de rutas como argumentos y Path.Combine se encargará de combinarlos correctamente, teniendo en cuenta los separadores de directorio adecuados para el
sistema operativo.
