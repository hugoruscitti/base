sharedot
========

Sharedot es un servidor web para compartir archivos, pensando para eventos de
tecnología y sprints de programación, en donde muchas veces no se cuenta con
acceso a Internet.

Sharedot está inspirado en piratebox, aunque requiere equipos con recursos
suficientes para utilizar celery, flask y gunicorn.

![](https://raw.github.com/hugoruscitti/sharedot/master/preview.png)


Agradecimientos
---------------

Usamos el código inicial que escribió [kcarnold](https://github.com/kcarnold),
[flask-gevent-socketio-chat](https://github.com/kcarnold/flask-gevent-socketio-chat),
para tener un código inicial de integración con socketio y flask.


Un buen comienzo para investigar es la biblioteca de 
[Alexandre Bourget](https://github.com/abourget) y su biblioteca
[gevent-socketio](https://github.com/abourget/gevent-socketio).

También hay una presentación muy buena de Bourget en Youtube donde muestra
algunos conceptos:

http://youtu.be/zhh_N5pmHBY?t=24m52s

Cómo instalarlo
---------------

Es aconsejable comenzar con un entorno virtual, algo así:

    mkvirtualenv sharedot
    pip install -r requirements.txt
    python server.py

Luego ingresa en la aplicación en http://localhost:8000
