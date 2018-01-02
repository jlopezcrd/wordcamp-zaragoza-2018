# wordcamp-zaragoza-2018
Taller del Wordcamp zaragoza celebrado en enero de 2018

## Instalación de Docker
https://www.docker.com/community-edition#/download

## Clona el repositorio
https://github.com/jlopezcrd/wordcamp-zaragoza-2018.git

## Crea un fichero .env
Creamos un fichero .env, (sí, con punto delante para que sea oculto) en el directorio del proyecto clonado con los siguientes datos:

```bash
MYSQL_ROOT_PASSWORD=TUPASSWORD
MYSQL_DATABASE=TUPASSWORD
MYSQL_USER=TUPASSWORD
MYSQL_PASSWORD=TUPASSWORD
```

## Inicia el proyecto
```bash
docker-compose up
```
