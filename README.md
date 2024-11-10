# Sistema de gestión de inventario
Un sencillo sistema de gestión de inventario construido con Django. Los usuarios pueden añadir artículos de stock y generar facturas. Todos los datos se almacenan en la base de datos y se muestran en tiempo real.
Para ejecutar el proyecto, ejecute los siguientes comandos en el directorio del proyecto para crear la base de datos. Al ejecutar el software por primera vez, es necesario ejecutar cada comando para cada aplicación en el proyecto
```
python manage.py makemigrations homepage
python manage.py migrate homepage
python manage.py makemigrations inventory
python manage.py migrate inventory
python manage.py makemigrations transactions
python manage.py migrate transactions
```
Después de la primera vez, se puede ejecutar lo siguiente para migrar los cambios de modelo en cualquier app
```
python manage.py makemigrations
python manage.py migrate
```
Utilice el siguiente comando para ejecutar el servidor
```
python manage.py runserver
```
Usa el siguiente comando para crear un usuario administrador
```
python manage.py createsuperuser
```
