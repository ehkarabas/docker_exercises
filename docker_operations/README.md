<div align=center>
	<h1>Docker Operations</h1>
</div>

_Wait a while for the explanatory gif to load..._


<div align="center">
	<img src="./presentation/docker_operations-presentation.gif"/>
</div>

## Description

A projects frontend and backend which are seperately dockerized.

## Goals

Practicing on building & renaming images, creating and starting containers via daemon on specified external/internal ports, stopping containers in bulk, removing images & containers  in bulk, effectively using Docker Desktop and VSCode Docker extension to check up-to-date condition of images and containers, docker hub operations(login/logout/push/pull).

## Installation

To run docker on your local, you need to download [Docker Desktop](https://www.docker.com/products/docker-desktop/) and then install on your OS. Make sure your docker engine(Docker Desktop) is running in background when you run all docker commands on your terminal.

You can check if docker has been successfully installed on your system or not via command below.
    ```
    $ docker --version
    ```
If all are OK, you can try commands shown on explanatory gif(you can download and convert it to mp4 to fast forward/backward on your desire) above.


## Resource Structure 

```
docker_operations(folder)
|
├── backend
│   ├── db.sqlite3
│   ├── dockerfile
│   ├── main
│   │   ├── asgi.py
│   │   ├── __init__.py
│   │   ├── __pycache__
│   │   │   ├── __init__.cpython-311.pyc
│   │   │   ├── settings.cpython-311.pyc
│   │   │   └── urls.cpython-311.pyc
│   │   ├── settings.py
│   │   ├── urls.py
│   │   └── wsgi.py
│   ├── manage.py
│   ├── README.md
│   ├── requirements.txt
│   └── tutorial
│       ├── admin.py
│       ├── apps.py
│       ├── __init__.py
│       ├── migrations
│       │   ├── 0001_initial.py
│       │   ├── __init__.py
│       │   └── __pycache__
│       │       ├── 0001_initial.cpython-311.pyc
│       │       └── __init__.cpython-311.pyc
│       ├── models.py
│       ├── __pycache__
│       │   ├── admin.cpython-311.pyc
│       │   ├── apps.cpython-311.pyc
│       │   ├── __init__.cpython-311.pyc
│       │   ├── models.cpython-311.pyc
│       │   ├── serializers.cpython-311.pyc
│       │   ├── urls.cpython-311.pyc
│       │   └── views.cpython-311.pyc
│       ├── serializers.py
│       ├── tests.py
│       ├── urls.py
│       └── views.py
├── docker-compose.yml
├── frontend
│   ├── dockerfile
│   ├── package.json
│   ├── package-lock.json
│   ├── public
│   │   ├── favicon.ico
│   │   ├── index.html
│   │   ├── logo192.png
│   │   ├── logo512.png
│   │   ├── manifest.json
│   │   └── robots.txt
│   ├── README.md
│   ├── src
│   │   ├── App.js
│   │   ├── components
│   │   │   ├── AddTutorial.jsx
│   │   │   ├── EditTutorial.jsx
│   │   │   └── TutorialList.jsx
│   │   ├── index.js
│   │   └── pages
│   │       └── Home.jsx
│   └── yarn.lock
├── presentation
│   └── docker_operations-presentation.gif
└── README.md
```


