1.- Para activar el entorno virtual se usa el comando: pipenv shell
2.- Para poder correr el web service se usa el comando: python manage.py runserver
    El nombre manage.py puede variar dependiendo del nombre del archivo.
3.- Para saber la ruta de tu entorno virtual ejecuta el comando: pipenv --venv
4.- Para crear una app se necesita usar el comando: python manage.py startapp core
    - El nombre manage.py varia dependiendo el nombre de la clase con la que estes trabajando
    - El nombre core es el nombre que tu le das a la clase de la aplicacion, puede variar 
      dependiendo de la decicion del desarrollador.

1. Ejecutar comando `git fetch` para revisar cambios pendinetes
2. Ejecutar comando `git pull` para actualizar el proyecto
3. Ejecutar comando `pip install -r requirements.txt` para instalar librerias
4. Ejecutar servidor con el comando:      


1. Ejecutar comando ``git add .`` para seleccionar los archivos modificados
2. Ejecutar comando ``git commmit -m "Mensaje"``
3. Ejecutar comando "git push"

Notas:
1.- Nunca utilizar enlaces encrudos, siempre utilizar Tag {% url %}
2.- el comando {% firtsof %} funciona para que te diga cual es la primera variable que no esta vacia
    En caso de que todas las variables esten vacias o no existan, puedes poner un nombre por defecto.
    De este modo sabes si una variable esta vacia sin necesidad de usar muchos {% if %}
