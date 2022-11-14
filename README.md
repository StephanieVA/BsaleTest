# BsaleTest

### INTRODUCCION

Se uso la API para consultar información de la base de datos y mostrar en detalle en la pagina web.

### CONFIGURACION
- Abrir terminal y ejecutar el siguiente comando "npm init -y", para que podamos instalar modulos de node js para la configuración del API.
- Luego "npm i express", que nos ayudara a conectarnos
- Además debemos de installar cors, dotenv, express, mysql2, nodemon
- El archivo package.json debe que asi:
![package ](https://user-images.githubusercontent.com/66794568/201575503-3cee870e-77ca-49b4-a67c-c3d5d39a5395.png)
- En la carpeta src encontramoslos archivos:
  1. Carpeta controllers: Encontramos las consultas a la bases de datos tanto de categoria y productos
  2. Carpeta bd: Aqui esta la conexion a la base de datos
  3. Carpeta routes: Se encuentra las urls de consulta para obtener los datos tanto de categoria y productos, como los id y name.
  4. Archivo app: Se encuentra un url añadido a las urls de los routes para una consulta de apis, además de la const cors que nos ayudara a obtener los datos dandonos autorización para a consulta.
  5. Archivo config: Esta las variables para la conexion de la base de datos.
  6. Archivo index :Se encuentra el port deonde se podra visualizar los urls de consultas.
 - Los urls de consultas son 4 y son las siguientes:
  1. Consultar todas los producto
  2. Consultar todas las categorias
  3. Consultar los productos por id de categorias
  4. Consultar los productos por nombre

