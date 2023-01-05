# Dockerizando una aplicación de Spring Boot

Segun requeria el ejercicio:

* Clonamos el repositorio indicado: https://github.com/heroe-geek/rest-api-springboot-mvc
* Creamos y configuramos el archivo Dockerfile
* Realizamos las pruebas correspondientes

Para ejecutar el API en docker necesitamos tener el mismo instalado y configurado, y ejecutar los siguientes comandos:

* Crear la imagen en docker: docker build -t "nombre de la imagen" .
* Correr la imagen de docker : docker run --name prueba -p 8080:8080 "nombre de la imagen":latest

Video ejecutando el API desde docker : https://youtu.be/Eo8_6PsAh3k
