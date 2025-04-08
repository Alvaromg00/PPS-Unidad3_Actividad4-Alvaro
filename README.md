# Explotación y mitigación de SQL Inyection

Vamos a realizar diferentes pruebas sobre inyección SQl y su mitigación:

## Creando base de datos y tablas

Vamos a crear dentro de la base de datos de **PHPMyAdmin** de la pila LAMPP una base de datos con una tabla de usuarios que almacena el usuario y la contraseña:

También añadimos los usuarios *admin* y *usuario*

![Creando db](./Imagenes/1.png)

Para comprobar que esta creado correctamente accedemos a la base de datos y consultamos el contenido de la tabla de usuarios:

![Creando db](./Imagenes/2.png)

## Inyección SQL

Vamos a crear un fichero llamado [login1.php](./Recursos/login1.php)
