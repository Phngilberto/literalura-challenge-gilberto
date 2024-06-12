Literalura
Descripción breve de tu proyecto y su objetivo. Este proyecto fue realizado para cumplir con el Challenge de Spring del programa de Alura con Oracle

Características
Busca libros en la API de Gutendex.
Muestra detalles de libros, incluidos diferentes formatos disponibles.
Descarga, ve en línea o escucha audiolibros.
Métodos asincrónicos para consultas rápidas a la API.
Recorrido completo de las más de 2900 páginas de la API.
Puedes buscar a través de diferentes filtros.
También puedes eliminar libros para que ya no aparezcan en tus búsquedas.
Puedes guardar tus favoritos
Entidades y sus Vinculaciones
libro
id : Identificador único del libro.
titulo : Título del libro.
cantidadDescargas : Número de descargas del libro.
tipoDeMedio : Tipo de medio del libro (por ejemplo, texto, audio).
autores : Lista de autores del libro (relación muchos a muchos con la entidad Autor).
lenguaje : Lenguaje en el que está escrito el libro.
categoria : Categoría del libro.
formatos : Lista de formatos disponibles para el libro (por ejemplo,Ver en línea, Descargar PDF, ePub, audiolibro).
imagen : URL de la imagen de la portada del libro.
estado : Permite dar de baja para poder ocultar los libros que no deseas ver.
Autor
id : Identificador único del autor.
nombre : Nombre del autor.
anioNac : Año de nacimiento del autor.
anioMuerte : Año de muerte del autor (si aplica).
Acceso a biografía : Los autores tienen un enlace a su biografía en wikipedia.
Las entidades Libroy Autortienen una relación de muchos a muchos. Esto significa que un libro puede tener múltiples autores y un autor puede haber escrito múltiples libros. La relación se maneja mediante una tabla intermedia autor_libro.

Tecnologías Utilizadas
Java
Bota de primavera
hoja de tomillo
HTML
CSS
Ejemplos de uso
Instalación
Clona este repositorio.
Abra el proyecto en su IDE preferido.
Configure las credenciales de la API de Gutendex en el archivo de propiedades ( application.propertieso application.yml).
Ejecute la aplicación.
Contribuir
Las contribuciones son bienvenidas. Por favor, sigue estas instrucciones:

Haz un tenedor del proyecto.
Crea una nueva rama ( git checkout -b feature/nueva-caracteristica).
Haz tus cambios y realiza un commit ( git commit -am 'Agrega nueva característica').
Haz empujar a la rama ( git push origin feature/nueva-caracteristica).
Abra una solicitud de extracción.
Créditos
Este proyecto fue creado por Gilberto Rodríguez.
