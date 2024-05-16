# Control Clientes

## Descripción

Control clientes es una aplicación desarrollada como parte del curso de "Universidad Java" en Udemy, con el proposito de practicar el uso del framework Spring para el desarrollo de aplicaciones web. La aplicacion permite gestionar usuarios con saldo, calcular la cantidad total de usuarios y el saldo total de los mismos. La interfaz de usuarios está implemetada utilizando bootstrap para un diseño moderno y responsivo.

## Requisitos previos

- Para la base de datos se requiere una base de datos MySQL o similar. Por mi parte usaré un contenedor de docker donde corra la base de datos.

## Tecnologías utilizadas
- java
- mysql
- spring
- springboot
- thymeleaf
- bootstrap
- html

## Instrucciones de uso:

1. Clona el repositorio en tu maquina local.
2. Asegurarse de tener instalado el contenedor de docker para correr la base de datos.
3. Navega hast el directorio donde se encuentra el proyecto y ejecuta el siguiente comando para iniciar la base de datos mySQL:
    ```bash
    docker-compose up -d
    ```
4. Abre el proyecto en tu ide preferido.
5. Accede a la url http://localhost:8080/ para ver la pagina de inicio y loguin.

## Notas adicionales:

- Las credenciales predeterminadas para acceder a la app son.
    - usuario: root
    - password: root
- Este proyecto es solo con fines educativos y de preactica.