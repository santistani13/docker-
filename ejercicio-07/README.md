1) Estan corriendo dos contenedores diferentes
2) un contenedor esta basado en la imagen postgres:14.4-alpine, y el otro esta basada en la nicopaez/jobvacancy-ruby:1.3.0
IN US
3) este decoker compose esta compuesto por dos servicios basados en dos imagenes, una para la webapp y otra para la db. Y en cada servicio se especifica la configuracion del mismo para que la aplicacion levante. 
4)Para esta pregunta estuve buscando un poco mas de informacion. Y por lo que entendi es que en la configuracion del web le estamos linkeando y agregando el depends para que el web dependa de la db