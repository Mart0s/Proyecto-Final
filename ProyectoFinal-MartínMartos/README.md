# ProyectoFinal-MartínMartos
Este proyecto es desarrollado en Python utilizando el framework Django. 
El proyecto trata de una página web enfocada a recopilar logotipos creados por usuarios, donde cada quien puede subir sus creaciones junto a un título, subtítulo y descripción.
La información es almacenada en la base de datos, y se puede chequear en todo momento. 

# Video Demostración.
https://youtu.be/-H87qxX9Zgs

_______________________________________________________________________________________________________________________________________________________________________
# DOCUMENTACIÓN.
Para correr el programa, primeramente debe de abrir el archivo con VSCode. Seguido de esto, en la terminal realizar los siguientes comandos:
1) python manage.py startapp mi_blog
2) python manage.py migrate
3) python manage.py makemigrations
4) python manage.py runserver
Realizado esto, abrimos la página http://127.0.0.1:8000

Los archivos son: models.py, forms.py, urls.py, views.py,la carpeta de templates, entre otros.

_______________________________________________________________________________________________________________________________________________________________________
# Models.py:
Acá se encuentran los modelos de datos usados por el backend.

Descripción: modelo Post. 
Campos: titulo (titular del post), subtitulo (subtexto del post), texto (descripción del post), imagen (foto del post), fecha_publicacion (fecha de publicacion del post), autor (creador del post).

Descripción: modelo Avatar. 
Campos: user (la cuenta registrada en el sitio), imagen (foto de perfil de la cuenta).

Descripción: modelo Mensaje. 
Campos: email (dirección de correo electrónico del usuario), nombre (nombre del usuario), texto (texto del mensaje), enviado_el (fecha de emisión del mensaje).
_______________________________________________________________________________________________________________________________________________________________________
# Forms.py:
Acá se encuentran los formularios usados para cargar los datos que quedarán guardados en nuestra base de datos.
Son tres formularios, uno para registrar los usuarios nuevos, y los otros dos son para registrar su contraseña.
_______________________________________________________________________________________________________________________________________________________________________
# Urls.py:
Contiene cada una de las rutas de las vistas de la app. 
_______________________________________________________________________________________________________________________________________________________________________
# Views.py:
Aparecen todas las vistas que se utilizan en la app.
_______________________________________________________________________________________________________________________________________________________________________
# Templates:
Acá se encuentran todos los archivos HTML usados por la app.

_______________________________________________________________________________________________________________________________________________________________________
# Autor: Juan Martín Martos
