# Instalar Postgres
1. Actualizar lista de paquetes
```bash
sudo apt update
```
2. Instalar Postgres
```bash
sudo apt install postgresql
```
3. Iniciar y gestionar el servidor PostgreSQL
Aunque capaz ya viene esto, pero lo ponemos igualmente :)

```bash
sudo systemctl start postgresql
sudo systemctl enable postgresql
```
Con el siguiente comando podemos ver el estado, estara activo.
```bash
sudo systemctl status postgresql
```
4. Entramos al usuario postgres
```bash
sudo su - postgres
```
Indicamos la contraseña de nuestro usuario, claro, dando por hecho que estamos en un usuario con permisos de `sudo`.
5. Ingresamos al cliente `psql` para interactuar con el servidor
Ejecutamos 
```
psql
```
6. Ajustar el acceso y cambiar la configuración de red

7. 
