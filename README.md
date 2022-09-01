# java-shell

Es un programa que permite generar codigos QR para dircciones url de sitios webs o redes sociales, consiste en escribir la Url y generar la imagen en formato Base64

## Requisitos

* Consola de Comandos

## Instalación

Una vez descargado el proyecto, en la consola, se ubica en la carpeta del proyecto, en la carpeta dist, dónde se encuentra el ejecutable.

## Comando
```sh
java -jar NombreApp.jar
```

## Pasos de Instalación y uso
* Instalación 

Una vez descargado el proyecto, en la consola de comandos nos ubicamos en la carpeta dist y utilizamos el comando

```sh
java -jar NombreApp.jar
```

Esto iniciará el programa y hará que aparezca el menú con las diferentes opciones.

## Uso
Una vez ejecutado el comando se mostrará un menú con diferentes opciones:

* Iniciar sesión
* Registrarse 
* Salir

Donde: 
- **_Iniciar Sesión:_** Se iniciará sesión con el usuario previamente registrado en el aplicativo
- **_Registrarse:_** Se registra un nuevo un nuevo usuario en la base de datos, ingresando un nombre, email, username y password
- **_Salir:_** Cerrará el programa

Al iniciar sesión correctamente aparecerá un nuevo menú:
- **_Generar codigo QR colocando la url_**
- **_Verificar historial de QR generados_** 
- **_Cerrar sesión_**

Donde:
- **_Generar código QR:_** se ingresa la url a convertir en imagen base64
- **_Verificar historial:_** se visualiza el historial de Qr en formato imagen base64 que se han generado
- **_Cerrar Sesión:_** Cerrará sesión del programa

