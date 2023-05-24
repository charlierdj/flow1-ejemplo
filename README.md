# flow1-ejemplo
**Primero de los trabajos y ejercicios exportados desde el contenedor de NodeRED desde docker compose.**

## Introducción

El flow 1 representa el primer ejercicio a realizar con NodeRed. Este ejercicio consiste únicamente en conectar un nodo Inject con un nodo Debug y automatizarlo para que genere un TimeStamp cada 5 segundos. Esta acción permite demostrar el uso de la pestaña Debug.

## Material Necesario

Para realizar este flow necesitas lo siguiente

- [Ubuntu 22.04 LTS](https://releases.ubuntu.com/22.04/)
- [Docker Engine](https://docs.docker.com/engine/install/ubuntu/#install-using-the-convenience-script)
- [NodeRed](https://nodered.org/docs/getting-started/local)

## Material de referencia

En los siguientes enlaces puedes encontrar cursos en la plataforma de edu.codigoiot.com que te permitirán realizar las configuraciones necesarias

- [Instalación de Virtual Box y Ubuntu 22.04](https://edu.codigoiot.com/course/view.php?id=812)
- [Introducción a Docker](https://edu.codigoiot.com/course/view.php?id=996)
- [Aplicacion multicontenedor de servidor IoT con Docker compose](https://edu.codigoiot.com/mod/lesson/view.php?id=3889&pageid=3804&startlastseen=no)
- [Introducción a NodeRed](https://edu.codigoiot.com/course/view.php?id=278)

## Instrucciones

### Requisitos previos

Para que este flow funcione, debes cumplir con los siguientes requisitos previos
1. Tener instalado Docker Engine.
2. Tener instaldo nodeRed por Docker Compose
3. Tener el contenedor de NodeRed con el volumen de data activado

### Instrucciones de preparación del entorno

Para ejecutar este flow, es necesario lo siguiente
1. Arrancar el contenedor de NodeRed con el comando
        
        sudo docker start $(sudo docker ps -a -q)

2. Dirigirse a [localhost:1880](localhost:1880)
3. Importar el flow desde el repositorio
4. Hacer clic en el boton Deploy

### Instrucciones de operación

Para observar el resultado de este flow, sólo es necesario abrir la pestaña Debug.

## Resultados

A continuación puede verse una vista previa del resultado de este flow.

![](https://github.com/charlierdj/flow1-ejemplo/blob/6ebd9f878817b4376f2d93be77a750d5b2de76c7/Imagenes/Screenshot%20from%202023-05-23%2021-53-05.png?raw=true)

## Evidencias

- [TikTok del profesor Hugo Escalpelo](https://www.tiktok.com/@hugoescalpelo/video/7236589590008564998)
- [YouTube (versión anterior)](https://youtu.be/8U-K6bgMQwE)

# Créditos

Desarrollado por el desarrollador del curso IoT Hugo Escalpelo
- [hugoescalpelo.com](https://hugoescalpelo.com/)
- [Página en Facebook](https://www.facebook.com/Hugo-Escalpelo-Profesional-337708683840136)
- [GitHub](https://github.com/hugoescalpelo)

Copiado por Carlos Rosales de Jesus
- [Mi Letterboxd](https://letterboxd.com/charlie_rdj/)