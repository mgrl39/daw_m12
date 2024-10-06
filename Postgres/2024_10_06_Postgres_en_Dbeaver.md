# Postgres 🐘 desde DBeaver 🦫 (Acceder remotamente)
Para conectarte a PostgreSQL debe estar la configuracion remota configurada. Y las maquinas deben poder verse entre ellas. Hay que asegurarse que las conexiones remotas sean correctas.

## 1. Instalacion DBeaver 🦫
Ejecutaremos el siguiente comando para instalar `BBeaver`.
```bash
sudo snap install dbeaver-ce
```
![Imagen de como se instala Dbeaver](img/dbeaver/dbeaver_001.PNG)
![Imagen de la instalacion correcta de Dbeaver](img/dbeaver/dbeaver_002.PNG)

## 2. Abrimos el programa
Podemos abrirlo desde el menu del ordenador o desde la terminal ejecutando `dbeaver-ce`.

## 3. Dentro del programa
Dentro se nos abrira la interfaz del programa y delante una notificacion diceindonos si queremos crear una baase de datos simple. En mi caso le di a **No**.
![Imagen de como se ve el programa](img/dbeaver/dbeaver_004.PNG)
![Imagen de la notificacion de crear una bae de datos simple](img/dbeaver/dbeaver_003.PNG)

## 4. Conexion a la base de datos.
Despues de darle a **No**, directamente se me abrio esta pestaña. Si no se os abre automaticamente, en **Database**, la primera opcion es **New Database Connection**. Otra manera es darle a `Shift + Ctrl + N`.

Seleccionamos **PostgreSQL** y le damos a **Next**.
![Imagen del menu de seleccion de base de datos](img/dbeaver/dbeaver_005.PNG)

## 5. Configuracion de la conexion
Aqui debemos indicar la `IP del host`, la `database`, el `username` y la contra.

Para saber la IP de la maquina podemos ejecutar `ip -c a` en la maquina que contiene el servidor de base de datos.

Indico la direccion IP del host y mi password (que era `password`).

Finalmente, clicamos a Finish.
![Imagen del menu de configuracion de la conexion](img/dbeaver/dbeaver_006.PNG)

## 6. Instalacion de Drivers y preguntas
Es posible que salga la siguiente imagen, yo le di a **Do not share data**.
![Imagen del menu de statics collection](img/dbeaver/dbeaver_007.PNG)

Tambien, muy importante, la instalacion de los drivers. Claramente los descargaremos
![Imagen del menu de descarga de drivers](img/dbeaver/dbeaver_008.PNG)

## 7. Conexion Exitosa
Si hemos hecho todo bien, la conexion habra sido exitosa.
![Imagen de la conexion exitosa](img/dbeaver/dbeaver_009.PNG)
![Imagen de la conexion exitosa](img/dbeaver/dbeaver_010.PNG)
