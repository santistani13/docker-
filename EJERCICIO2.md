EJERCICIO 2: 
comandos:
docker run nicopaez/pingapp:3.0.0
docker tag nicopaez/pingapp:3.0.0 sstanicio/first-image:myimage
docker login 
docker push sstanicio/first-image:myimage

comando para pullear la img:
docker pull sstanicio/first-image:myimage
