# BsaleTest

### INTRODUCCION

Se uso la API para consultar información de la base de datos y mostrar en detalle en la pagina web.
Se uso el Node js para la configuracion de la API junto con JAVASCRIPT.

### OBJETIVO
- Dar a conocer las consultas de la API.
- Dar a conocer a los clientos los productos existentes

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
  1. Consultar todas los producto: https://bsaletest-production-c296.up.railway.app/api/product
  ![product](https://user-images.githubusercontent.com/66794568/201578622-43ec39b1-c431-47eb-9977-7965ee1de475.png)
  2. Consultar todas las categorias: https://bsaletest-production-c296.up.railway.app/api/category
  https://github.com/StephanieVA/BsaleTest/issues/5#issue-1447389490
  3. Consultar los productos por id de categorias: https://bsaletest-production-c296.up.railway.app/api/productCat/2
  ![productCat](https://user-images.githubusercontent.com/66794568/201578884-14947fa7-81dd-4243-8dc9-252ce429c3f6.png)
  4. Consultar los productos por nombre: https://bsaletest-production-c296.up.railway.app/api/productName
  ![productName](https://user-images.githubusercontent.com/66794568/201578838-a93934c0-438d-4442-9dca-982c3970e067.png)
