# INTEGRANTES: MIGUEL ANGEL AGUILAR Y SEBASTIAN ACOSTA MOLINA 

# PASOS PARA EL COMO EJECUTAR EL CODIGO
El proyecto se ejecuta, cuando tengamos la carpeta de usuario_project, ahi debemos tener el folder, usuario_project, usuarios y manage.py,
lo que vamos a hacer es crear un entorno virtual en este caso usamos python -m venv venv y lo activamos con venv\Scripts\activate, si no tenemos
instalado Django y sus dependencias entonces ponemos pip install django psycopg2-binary , ya con esto nos ubicamos en el manage.py y vamos a 
correr nuestra pagina con el comando python manage.py runserver y ya por ultimo entramos al navegador http://127.0.0.1:8000/ donde ya nos
aparecera el registro de usuario.

Ahora bien, en pgadmin iniciamos sesion y vamos a bases de datos, vamos a la de usuario_db, vamos a Schemas, bajamos a tablas y le damos
a view para ver los usuarios que han sido guardados en la base de datos 


