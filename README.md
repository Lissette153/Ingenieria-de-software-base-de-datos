Para ejecutar la aplicación debes hacer lo siguiente:

Instalar python, vs code, xampp y mysql.

Luego: 1: Pip install django -Tener instalado django 2: Pip install mysqlclient -Instalar mysqlclient 3. Conectarse a la base de datos con el xampp, iniciar localhost y mysql. Una vez hecho apretar admin mysql y crear la base de datos 'gasdb' 4: Ir al proyecto, importar las migraciones: python manage.py makemigrations y migrate 5. Si las tablas no se crean (models) crearlas con el script asignado que contiene el archivo. 6: Ejecutar la aplicación: python manage.py runserver.
