# boot_hello

## para importar a eclipse
mvn eclipse:eclipse

## build proyect 
mvn clean install

## Build docker
docker build -t dami/testp:0.1 .

## Correr Docker
docker run -e name=123 -p 8080:8080 dami/testp:0.1
