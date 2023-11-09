## Instructions for DockerFile
    
Comando para hacer la imagen

docker build -t docker-express

Comando para correr el contenedor 

docker run -d --name=express-daniel -p 7777:3000 docker-express