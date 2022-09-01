# java-shell

Es un programa que permite generar codigos QR para dircciones url de sitios webs o redes sociales, consiste en escribir la Url y generar la imagen en formato Base64

## Requisitos

* Consola de Comandos

## Instalación

En la consola, se ubica en la carpeta del proyecto, en la carpeta dist, dónde se encuentra el ejecutable.

## Comando
java -jar NombreApp.jar

## Pasos de Instalación y uso
* Instalación
una vez descargado el proyecto, en la consola de comandos nos ubicamos en la carpeta dist y utilizamos el comando
java -jar NombreApp.jar

Esto iniciará el programa y hará que aparezca el menú con las diferentes opciones.

## Uso
Una vez ejecutado el comando se mostrará un menú con diferentes opciones:

* Iniciar sesión
* Registrarse 
* Salir

Donde: 
* #### Iniciar Sesión: Se iniciará sesión con el usuario previamente registrado en el aplicativo
* #### Registrarse: Se registra un nuevo un nuevo usuario en la base de datos, ingresando un nombre, email, username y password
* #### Salir: Cerrará el programa

Al iniciar sesión correctamente aparecerá un nuevo menú:
* #### Generar codigo QR colocando la url 
* #### Verificar historial de QR generados 
* #### cerrar sesión

Donde: 
* #### Generar código QR: se ingresa la url a convertir en imagen base64
* #### Ver historial: se visualiza el historial de Qr que se han generado
* #### Cerrar Sesión: Cerrará sesión del programa
