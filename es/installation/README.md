# Instalación
Estamos a punto de configurar nuestro entorno para trabajar con Angular, los pasos son sencillos.
## Requisitos
Primero tienes que asegurarte de tener instalado lo siguiente:
  1. Git - Descargar e instalar [Git](https://git-scm.com/downloads)
  2. NodeJS - Descargar e instalar la última versión de [NodeJS](https://nodejs.org/es/)
  3. Editor de codigo: Puedes usar el de tu preferencia, si es que no cuentas con alguno puedes probar utilizando [Visual Studio Code](https://code.visualstudio.com/Download)

Con esto ya estamos listos para comenzar a configurar nuestro entorno.
## Preparando el entorno
Lo primero que tenemos que hacer es instalar **Angular CLI**, desde tu consola o terminal ejecuta el siguiente comando:
```sh
npm install @angular/cli -g
```
Este comando instalará de manera global angular-cli que te permite automatizar e iniciar aplicaciones de angular.

Una vez el comando termine, ejecuta:
```sh
ng -v
```
Este comando imprimirá en la consola un Arte ASCII de angular-cli y las versiones instaladas de los diferentes paquetes de la aplicación.

A partir de ahora puedes crear una aplicación de Angular con el comando “new”:
```sh
ng new mi-primera-aplicacion-angular
```
Se creará un directorio con el nombre del proyecto que hayas creado, entonces ahora necesitas ingresar al directorio:
```sh
cd mi-primera-aplicacion-angular
```
Ahora puedes ejecutar el siguiente comando:
```sh
ng serve
```
Tu aplicación comenzará en el puerto 4200:
```sh
http://localhost:4200/
```
Navega a la url y podrás ver corriendo tu primera aplicación de Angular!

![Alt Text](https://media1.tenor.com/images/60566e076cb41567efe97e3ed8a238d4/tenor.gif?itemid=4487134)
