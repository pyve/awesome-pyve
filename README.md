## Recursos compartidos vía la comunidad de Python Venezuela

- Índice:
    - [Análisis científico con Python](#análisis-científico-con-python)
    - [Frameworks basados en Python](#frameworks-basados-en-python)
    - [Hardware libre con Python](#hardware-libre-con-python)
    - [Herramientas para desarrollo y depuración de código](#herramientas-para-desarrollo-y-depuración-de-código)
    - [Recursos para el desarrollo de Backends](#recursos-para-el-desarrollo-de-backends)
    - [Recursos para el manejo de Bases de Datos](#recursos-para-el-manejo-de-bases-de-datos)
    - [Recursos para el desarrollo de Front-ends](#recursos-para-el-desarrollo-de-front-ends)
    - [Recursos para el despliegue de aplicaciones](#recursos-para-el-despliegue-de-aplicaciones)
    - [Servicios para el control de versiones](#servicios-para-el-control-de-versiones)
    - [Recursos para crear interfaces gráficas](#recursos-para-crear-interfaces-gráficas)
    - [Otros recursos útlies](#otros-recursos-útiles)
    - [Blog posts](#blog-posts)

- - -

## Análisis científico con Python

* [GraphLab Create](https://pypi.python.org/pypi/GraphLab-Create) - Librería programada en c++
de alto rendimiento para construcción de gráficos de con data de gran escala *(en inglés)*.
* [Pandas](http://pandas.pydata.org/) - Libreria de altor rendimiento y simple de usar para
realizar análisis y modelado de datos *(en inglés)*.


- - -

## [Frameworks](https://es.wikipedia.org/wiki/Framework) basados en Python

### Frameworks para desarrollo web
* [Django](https://www.djangoproject.com/) - Framework web de alto nivel, desarrollo rápido con diseño
limpio y pragmático
    * Complementos para Django   
        * [django-rest-framework](http://www.django-rest-framework.org/) - Framework para
          desarrollar [API](https://es.wikipedia.org/wiki/Interfaz_de_programaci%C3%B3n_de_aplicaciones) 
          basado en [REST](https://es.wikipedia.org/wiki/Representational_State_Transfer)  *(en inglés)*.
        * [django-rest-framework-gis](https://github.com/djangonauts/django-rest-framework-gis) -
          django-rest-framework con agregados para el manejo de datos geográficos con *Django*.
        * [django-model-utils](https://django-model-utils.readthedocs.org/en/latest/) -
          Utilidades para simplificar el uso de modelos en *Django (en inglés)* .
        * [celery](http://celery.readthedocs.org/en/latest/django/first-steps-with-django.html) -
          Tareas asincronicas distribuídas en tiempo real con *Django (en inglés)* .

* [Flask](http://flask.pocoo.org/) – Flask es un micro marco de trabajo que sirve para
construir aplicaciones web.

- - -

## Hardware libre con Python

### Bibliotecas para el desarrollo con [Arduino](https://www.arduino.cc/)
* [Arduino y Python](http://playground.arduino.cc/Interfacing/Python) - Herramientas para
establecer comunicación vía puerto serial con arduino a través de Python *(en inglés)*.
* [Arduino y Python Videos](http://playground.arduino.cc/Interfacing/Python) - 17 video
tutoriales para manejar arduino con Python *(en inglés)*.

### Bibliotecas para el desarrollo con [Raspberry Pi](https://www.raspberrypi.org/)
* [Raspberry Pi Teach](https://www.raspberrypi.org/resources/teach/) - Recursos
para aprender a programar Raspberry Py con python *(en inglés)*.

- - -

## Herramientas para desarrollo y depuración de código
* [iPython](http://ipython.org/) - Poderoso shell interactivo; cuenta con interfaz gráfica basadan en Qt e interfaz basada en navegador notebook con soporte para código, texto enriquecido, expresiones matemáticas, generador de gráficos entre otros.
* [pdb](https://docs.python.org/2/library/pdb.html/) - Depurador de *Python* acrónimo ingles pdb: Python Debugger. Soporta punto de interrupción condicionales y seguimiento paso a paso del código.


- - -

## Recursos para el desarrollo de [Backends](https://es.wikipedia.org/wiki/Front-end_y_back-end)

*Recursos para desarrollar componentes y servidores de backend*

* [celery](http://www.celeryproject.org/) - Libreria para el manejo de tareas asincrónicas
mediante mensajes distribuidos en tiempo real.
* [requests](http://docs.python-requests.org/en/latest/) – Una hermosa Librería
para manejar peticiones HTTP.
* [rq](http://python-rq.org/) – Librería para implementar colas de tareas usando
Redis

- - -

## Recursos para el manejo de Bases de Datos

* [ZODB](http://www.zodb.org/) - Base de Datos Orientada a Objetos nativa para *Python*.

### Conectores

* [psycopg2](http://initd.org/psycopg/) - *Psycopg* es el adaptador de
*PostgreSQL* más popular.
* [pymongo](http://api.mongodb.org/python/current/) - Conector para *MongoDB*
desde *Python*.
* [MySQL Connector](http://dev.mysql.com/doc/connector-python/en/) - Conector para *MySQL* desde *Python*.

### Herramientas y Mapeadores Objeto-Relacionales

* [SQLAlchemy][sqlalchemy] - SQLAlchemy es un 
[ORM](https://es.wikipedia.org/wiki/Mapeo_objeto-relacional) para python que incluye soporte 
para SQLite, MySQL, PostgreSQL, Oracle, MS SQL, entre otros que facilita la
programación orientada a objetos con los motores base de datos relacionales *(en inglés)*
* [Alembic](http://alembic.readthedocs.org/) - Herramienta ligera de migración
de bases de datos para [SQLAlchemy][sqlalchemy].

[sqlalchemy]: http://www.sqlalchemy.org/

- - -

## Recursos para el desarrollo de [Front-ends](https://es.wikipedia.org/wiki/Front-end_y_back-end)

*Los siguientes son recursos no tienen ninguna relación con Python pero son
sumamente útiles para el desarrollo de interfaces web.*

* [Bootstrap](http://getbootstrap.com/) – Es un framework HTML, CSS y JS para
crear aplicaciones web responsivas

* [Foundation](http://foundation.zurb.com/) – Es otro framework HTML, CSS y JS
para el desarrollo de aplicaciones web responsivas

* [PureCSS](http://purecss.io/) – Es un conjunto de módulos CSS muy pequeño que
se usa para desarrollar aplicaciones web responsivas. A diferencia de Bootstrap
y Foundation, PureCSS no contiene ningún módulo Javascript.

- - -

## Recursos para el despliegue de aplicaciones

* [fabric](http://www.fabfile.org/) – Es una librería Python basado en línea de comandos para
ejecutar aplicaciones o tareas administrativas locales o remotas través de 
[SSH](https://es.wikipedia.org/wiki/Secure_Shell)

- - -

## Servicios para el control de versiones

* [GitHub](https://github.com/) – Es uno de los servicios web más populares
que ofrece hosting gratuito para repositorios en Git, seguimiento de errores,
solicitudes de cambios y wikis. Ofrece repositorios privados pero de pago.

* [GitLab](https://gitlab.com/) – Es otro servicio web que ofrece hosting
gratuito para repositorios en Git, seguimiento de errores, solicitudes de
cambios y wikis. A diferencia de GitHub, GitLab ofrece repositorios privados
de forma gratuita (pero limitados)

* [Bitbucket](https://bitbucket.org/) – Es un servicio web que ofrece hosting
gratuito para no sólo para repositorios en Git sino también en Mercurial,
ofrece seguimiento de errores, solicitudes de cambios y wikis. También ofrece
repositorios privados de forma gratuita (pero limitados)
- - -

## Recursos para crear interfaces gráficas

* [pyqt](https://wiki.python.org/moin/PyQt) – Librería para crear interfaces
gráficas de escritorio usando Qt 4.x o Qt 5.x
* [PySide](https://wiki.qt.io/PySide) – Librería para crear interfaces gráficas
de escritorio usando Qt.
* [python-gtk3](http://python-gtk-3-tutorial.readthedocs.org/en/latest/) –
Librería para crear interfaces gráficas de escritorio usango Gtk+ 3

- - -

## Otros recursos útiles

* [click](http://click.pocoo.org/4/) – Click es una librería para manejar la
línea de comandos desde Python.
* [SaltStack](http://saltstack.com/community/) – Herramienta para gestión de infraestructuras y despliegue de aplicaciones.

- - -

## Blog posts

* [Drastically Improve Your Python: Understanding Python's Execution Model (inglés)](http://www.jeffknupp.com/blog/2013/02/14/drastically-improve-your-python-understanding-pythons-execution-model/) - Este post te ayudará a entender qué sucede internamente cuando se realizan tareas comunes como crear variables o llamar a una función.
* [Open Sourcing a Python Project The Right Way (inglés)](http://www.jeffknupp.com/blog/2013/08/16/open-sourcing-a-python-project-the-right-way/) –
Pasos para hacer tu proyecto open source de la mejor manera.

## Licencia

[![Creative Commons License](http://i.creativecommons.org/l/by/4.0/88x31.png)](http://creativecommons.org/licenses/by/4.0/)

Este trabajo tiene licencia [Creative Commons Attribution 4.0 International License](http://creativecommons.org/licenses/by/4.0/).
