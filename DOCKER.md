## DOCKER:

**docker pull hello-world**: para traerse las imágenes

**docker images**: para ver las imágenes que tengo

**docker run hello-world:latest**: ejecuta el contenedor de una imagen, también me lo baja si no me lo encuentra



**docker ps**: dockers activos

**CONTAINER ID   IMAGE     COMMAND   CREATED   STATUS    PORTS     NAMES**



**docker ps -a**: dockers activos o no activos

**CONTAINER ID   IMAGE                COMMAND    CREATED             STATUS                         PORTS     NAMES**

63446521bd7e   hello-world:latest   "/hello"   4 minutes ago       Exited (0) 4 minutes ago                 silly\_blackwell

aecf748f433b   hello-world          "/hello"   About an hour ago   Exited (0) About an hour ago             sweet\_bhaskara



**docker start 634 (Son los 3 primeros números del id del docker)**: iniciamos la imagen por id o nombre

**docker rmi** **hello-world**: borra imagen

**docker run**: ejecuta el contenedor de una imagen.

**docker stop**: detiene el contenedor de forma ordenada.

**docker rm 634**: elimina el contenedor

**nginx**: es un servidor web.

**-d**: ejecuta el contenedor en segundo plano.

**docker kill:**

**docker start:**

**Docker run -d -p puerto host:Puerto contenedor:** redirección de puertos.

**curl 127.0.0.1**:
<!DOCTYPE html>

<html>

<head>

<title>Welcome to nginx!</title>

<style>

html { color-scheme: light dark; }

body { width: 35em; margin: 0 auto;

font-family: Tahoma, Verdana, Arial, sans-serif; }

</style>

</head>

<body>

<h1>Welcome to nginx!</h1>

<p>If you see this page, the nginx web server is successfully installed and

working. Further configuration is required.</p>



<p>For online documentation and support please refer to

<a href="http://nginx.org/">nginx.org</a>.<br/>

Commercial support is available at

<a href="http://nginx.com/">nginx.com</a>.</p>



<p><em>Thank you for using nginx.</em></p>

</body>

</html>

