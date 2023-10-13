# FileX - Biblioteca de Manejo de Archivos

FileX es una biblioteca de Java que proporciona herramientas para el manejo de archivos. Puedes utilizar FileX para realizar operaciones comunes de lectura, escritura, creación, movimiento y eliminación de archivos en tus proyectos de Java.

## Contenido
- [Instalación](#instalación)
- [Uso Básico](#uso-básico)
- [Ejemplos](#ejemplos)
- [API](#api)
- [Preguntas Frecuentes](#preguntas-frecuentes)
- [Contribución](#contribución)
- [Licencia](#licencia)

## Instalación

Agrega el archivo JAR de FileX a tu proyecto Java siguiendo estos pasos:

1. [Descarga el último archivo JAR](#) de las versiones de la biblioteca.
2. Agrega el archivo JAR descargado a las dependencias de tu proyecto.

## Uso Básico
Crea una instancia de filex proporcionando la ruta del archivo que deseas manejar.
java
Copy code
filex archivo = new filex("ruta/al/archivo.txt");
Utiliza los métodos proporcionados por FileX para realizar operaciones en el archivo, como lectura, escritura, creación, movimiento y eliminación.
Ejemplos
A continuación, te mostramos algunos ejemplos de uso de FileX:

java
Copy code
// Crear un nuevo archivo
archivo.createFile("nuevo-archivo.txt");

// Escribir en el archivo
archivo.writerFile("Este es un ejemplo de texto.");

// Leer el contenido del archivo
String contenido = archivo.readerFile();
System.out.println("Contenido del archivo: " + contenido);

// Mover el archivo a una nueva ubicación
archivo.moveFile("nueva-ruta/archivo.txt");

// Eliminar el archivo
archivo.removeFile();
API
La API de FileX ofrece las siguientes funciones:

createFile(ruta): Crea un nuevo archivo en la ruta especificada.
writerFile(texto): Escribe el texto proporcionado en el archivo.
readerFile(): Lee el contenido del archivo.
moveFile(rutaDestino): Mueve el archivo actual a una nueva ubicación.
removeFile(): Elimina el archivo actual.
Para obtener más detalles sobre los métodos y ejemplos de uso, consulta la documentación completa.

Preguntas Frecuentes
¿Tienes preguntas o problemas? Consulta nuestra sección de preguntas frecuentes para obtener respuestas a las dudas comunes.

Contribución
¡Tu contribución es bienvenida! Si deseas contribuir al desarrollo de FileX, consulta nuestras pautas de contribución.

Licencia
FileX se distribuye bajo la Licencia MIT. Para más información, consulta el archivo LICENSE.

Para comenzar a utilizar FileX en tu proyecto, sigue estos pasos:

1. Importa la biblioteca en tu archivo Java:

```java
import com.filex.filex;
