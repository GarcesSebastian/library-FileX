# FileX - Libreria de Manejo de Archivos

FileX es una Libreria de Java que proporciona herramientas para el manejo de archivos. Puedes utilizar FileX para realizar operaciones comunes de lectura, escritura, creación, copiar, movimiento y eliminación de archivos en tus proyectos de Java.

## Contenido
- [Instalación](#instalación)
- [Uso Básico](#uso-básico)
- [Ejemplos](#ejemplos)
- [Libreria](#libreria)
- [Compatibilidad](#compatibilidad)
- [Licencia](#licencia)

## Instalación

Agrega el archivo JAR de FileX a tu proyecto Java siguiendo estos pasos:

1. [Descarga el último archivo JAR](#) de las versiones de la libreria.
2. Agrega el archivo JAR descargado a las dependencias de tu proyecto.

## Uso Básico

Para comenzar a utilizar FileX en tu proyecto, sigue estos pasos:

1. Importa la libreria en tu archivo Java:

```java
import com.filex.filex;
```

2. Crea una instancia de filex proporcionando la ruta del archivo que deseas manejar:
```java
filex archivo = new filex("ruta/al/archivo.txt");
```

3. Utiliza los métodos proporcionados por FileX para realizar operaciones en el archivo, como lectura, escritura, creación, copiar, movimiento y eliminación.

## Ejemplos
A continuación, te mostramos algunos ejemplos de uso de FileX:
```java
// Crear un nuevo archivo
archivo.createFile("nuevo-archivo.txt");

// Escribir en el archivo
archivo.writerFile("Este es un ejemplo de texto.");

// Leer el contenido del archivo
String contenido = archivo.readerFile();
System.out.println("Contenido del archivo: " + contenido);

// Copia el archivo a una nueva ubicación conservando el nombre
archivo.copyFile("nueva-ruta/");

// Mover el archivo a una nueva ubicación conservando el nombre
archivo.moveFile("nueva-ruta/");

// Eliminar el archivo
archivo.removeFile();
```
## Libreria
La Libreria de FileX ofrece las siguientes funciones:

1. `createFile(ruta)`: Crea un nuevo archivo en la ruta especificada.
2. `writerFile(texto)`: Escribe el texto proporcionado en el archivo.
3. `readerFile()`: Lee el contenido del archivo.
4. `copyFile(rutaDestino)`: Copia el archivo actual a una nueva ubicación conservando el nombre.
5. `moveFile(rutaDestino)`: Mueve el archivo actual a una nueva ubicación conservando el nombre.
6. `removeFile()`: Elimina el archivo actual.

Para obtener más detalles sobre los métodos y ejemplos de uso, consulta la [documentación completa](https://github.com/GarcesSebastian/library-FileX/tree/main/docs).

## Compatibilidad

FileX es compatible con:

- Java 8 y versiones superiores.

Asegúrate de utilizar una versión de Java que sea compatible con FileX en tu proyecto. Si tienes dudas sobre la compatibilidad con una versión específica, no dudes en consultar en la [sección de problemas de GitHub](https://github.com/GarcesSebastian/library-FileX/issues) para obtener asistencia.

## Licencia
FileX se distribuye bajo la Licencia MIT. Para más información, consulta el archivo [LICENSE](https://github.com/GarcesSebastian/library-FileX/blob/main/LICENSE.txt).
