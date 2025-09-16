<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo"></a></p>

# Guía de Instalación del Proyecto ICOJUVE

## Clonar el Repositorio

Clona el repositorio en tu máquina local:

```bash
git clone https://github.com/GabrielaPPP13/ICOJUVE.git
```

## Cambiar a tu Rama Personal

Navega al directorio del proyecto y cambia a la rama asignada a tu nombre:

```bash
git checkout <nombre-rama>
```

## Instalar Dependencias

### Dependencias de PHP

Ejecuta el siguiente comando para instalar las dependencias de PHP usando Composer:

```bash
composer install
```

### Dependencias de Node.js

Instala las dependencias de Node.js especificadas en package.json:

```bash
npm install
```

## Configurar el Entorno

Copia el archivo .env.example a .env:

```bash
cp .env.example .env
```

Abre el archivo .env y configura las variables de entorno necesarias, como la conexión a la base de datos:

```plaintext
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=nombre_de_la_base_de_datos
DB_USERNAME=usuario
DB_PASSWORD=contraseña
```

## Migrar la Base de Datos

Si el proyecto ya tiene migraciones, ejecuta el siguiente comando para configurar la base de datos:

```bash
php artisan migrate
```

## Guardar y Subir Cambios a tu Rama

Cuando realices cambios en el proyecto, sigue estos pasos para guardarlos y subirlos a tu rama en el repositorio remoto:

-   Añadir los cambios:

```bash
git add .
```

-   Confirmar los cambios:

```bash
git commit -m "Descripción de los cambios realizados"
```

-   Subir los cambios a tu rama en GitHub:

```bash
git push origin <nombre_de_tu_rama>
```

Asegúrate de reemplazar <nombre_de_tu_rama> con el nombre exacto de tu rama.

Con estos pasos deberías tener el proyecto en funcionamiento en tu entorno local. ¡Feliz desarrollo!
