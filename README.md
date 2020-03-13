<p align="center"><img src="https://res.cloudinary.com/dtfbvvkyp/image/upload/v1566331377/laravel-logolockup-cmyk-red.svg" width="400"></p>

<p align="center">
<a href="https://travis-ci.org/laravel/framework"><img src="https://travis-ci.org/laravel/framework.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://poser.pugx.org/laravel/framework/d/total.svg" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://poser.pugx.org/laravel/framework/v/stable.svg" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://poser.pugx.org/laravel/framework/license.svg" alt="License"></a>
</p>

# 1. PRIMERO DEBES INSTALAR 

>Instalar un servidor de aplicaciones Web Local:

En este proyecto vamos a utilizar XAMPP: que ya te incluye (php+apache+mysql)

![](imgxampp.png)

Instalar Composer:
es un manejador de dependencias que nos va permitir trabajar con laravel
en especifico para instalar LARAVEL.

![](imgcomposer.png)

# 2. COMO CREAR UN PROYECTO NUEVO EN LARAVEL

 <ul>
        <li>Usa tu editor de texto favorito en este caso vamos a usar Visual Studio Code.</li>
        <li>desde el editor de texto ingresa a la carpeta: 
        <ul>
        <li>disco local C:/</li>
        <li>Ingresa a la carpeta XAAMP</li>
        <li>Ingresa a la carpeta htdocs</li>
        <li>Luego desde Visual Studio Code ingresa a la terminal y escribe el siguiente comando:</li>
        </li>
        </ul>
         
   </ul>


`$ composer create-project --prefer-dist laravel/laravel sistema`


# 3. COMO CONECTAR LA BASE DE DATOS Y VAMOS A USAR LAS MIGRACIONES DE LARAVEL

Nos vamos a la extencion .env para configuar la Base de Datos

![](imgenv.png)


 abrimos nuestro navegador y nos dirigimos a PHPMyAdmin http://localhost/phpmyadmin/
 
![](phpmyadmin.png)

Creamos una nueva base de datos 
y le damos un nombre

esta base de datos es la que vamos a ligar con mi proyecto de LARAVEL 


Nos dirigimos a la siguiente ubicación de la extencion .env y modificamos solo las partes seleccionadas

![](imgDB.png)

 <ul>
        <li>En la primera opcion le agregamos el nombre de la base de datos que creamos en phpmyadmin</li>
        <li>en la segunda opcion agregamos root</li>
        <li>en la tercera no agregamos contraseña</li>
    </ul>








![](BD.png)













