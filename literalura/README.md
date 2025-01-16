# LiterAlura 📚✨
LiterAlura es una aplicación de consola para consultar libros de dominio público en varios idiomas. Desarrollada en Java con Spring Boot y PostgreSQL, se conecta a la API de Gutenberg para obtener y almacenar información de libros. Es parte del "Challenge One" del programa Alura ONE (Oracle Next Education). 

## ¿Como funciona?
LiterAlura es una aplicación de consola desarrollada en Java con Spring Boot y PostgreSQL. Se conecta a la [API de Guntendex][1] para obtener información sobre libros de dominio público y almacenarla en una base de datos PostgreSQL.

Al iniciar la aplicación, se muestra un menú con opciones para buscar libros, consultar libros guardados, consultar autores, consultar autores por año y consultar libros por idioma. Al buscar un libro, se obtiene la información de la API y se guarda en la base de datos. Las opciones de consulta permiten visualizar los datos almacenados.

## ¿Como utlizarlo?
1. Clone o descargue el proyecto [aqui][2]
2. Inicie la carpeta del proyecto en IntelliJ
3. Configure su archivo application.properties
4. Ejecute la clase LiterAluraApplication

> Nota: 
> Recuerde que debe contar con una instancia de base de datos en postgresql ya que se creara las respectivas tablas al ejecutar la aplicación.

## Tecnologias utilizadas
![Postgres][image-1]
![Postman][image-2]
![Spring][image-3]
![Java][image-4]
![IntelliJ IDEA][image-5]
![Git][image-6]

[1]:	https://gutendex.com/
[2]:	https://github.com/IsaacCuautle/LiterAlura/releases/download/v1.0.0/LiterAlura-main.zip

[image-1]:	https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white
[image-2]:	https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white
[image-3]:	https://img.shields.io/badge/spring-%236DB33F.svg?style=for-the-badge&logo=spring&logoColor=white
[image-4]:	https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white
[image-5]:	https://img.shields.io/badge/IntelliJIDEA-000000.svg?style=for-the-badge&logo=intellij-idea&logoColor=white
[image-6]:	https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white