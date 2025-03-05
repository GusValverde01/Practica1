Esta práctica tuvo como propósito crear un sistema login completo, con el registro de usuarios, tipos de usuarios (admin y usuario), un CRUD completo para el área de administración y la utilización del algoritmo BCrypt para encriptar contraseñas. Además de conocer las dependencias adecuadas para la correcta realización del proyecto, tales como spring-security-crypto (para encriptar password), spring-boot-starter-thymeleaf (para los archivos html), etc. 
Para llevar a cabo la ejecución de la aplicación es necesario hacer lo siguiente: 

En la carpeta de src, accediendo a la carpeta de de main -> java se encuentra el controlador "Practica1Application.java" para correr el proyecto. 
Para ejecutar el proyecto, clona el reposiorio con: git clone https://github.com/GusValverde01/Practica1.git 

Deberás cambiar el puerto mysql al que usa tu computadora en application.properties

La db del proyecto viene en el schema.sql

Accede a la carpeta del proyecto: cd Practica1 ejecutas el proyecto con maven: mvn spring-boot:run 

accedes al endpoint en el navegadr con: http://localhost:8080/login

![image](https://github.com/user-attachments/assets/ff6bb321-5b7e-4934-a4f8-57271902d0be)

