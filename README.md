
EJERCICIO 1:
Dejo abajo el comando que fui ejecutando para el primer ejercicio y la respuesta de la misma. 
tambien dejo el archivo index.html
docker run -d -p 8083:80 --name index-nginx -v C:\Users\SStanicio\carpetaDocker:/usr/share/nginx/html nginx
e9d60220451adaed6b053b5353674310b1767c8a8c3dfef688f95ab7ed6340c2

EJERCICIO 2: 
comandos:
docker run nicopaez/pingapp:3.0.0
docker tag nicopaez/pingapp:3.0.0 sstanicio/first-image:myimage
docker login 
docker push sstanicio/first-image:myimage

comando para pullear la img:
docker pull sstanicio/first-image:myimage

