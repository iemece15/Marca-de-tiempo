# flow1-g12
contiene el flow 1 de la leccion de Node RED

## Introducción

El flow 1 representa el primer ejercicio a realizar con NodeRed. Este ejercicio consiste únicamente en conectar un nodo Inject con un nodo Debug y automatizarlo para que genere un TimeStamp cada 1 segundo. Esta acción permite demostrar el uso de la pestaña Debug.

## Material Necesario

Para realizar este flow necesitas lo siguiente

- [Ubuntu 20.04](https://releases.ubuntu.com/20.04/)
- [Docker Engine](https://docs.docker.com/engine/install/ubuntu/#install-using-the-convenience-script)
- [NodeRed](https://nodered.org/docs/getting-started/local)

## Material de referencia

En los siguientes enlaces puedes encontrar cursos en la plataforma de edu.codigoiot.com que te permitirán realiar las configuraciones necesarias

- [Instalación de Virutal Box y Ubuntu 20.04](https://edu.codigoiot.com/course/view.php?id=812)
- [Introduccion a Docker](https://edu.codigoiot.com/course/view.php?id=996)
- [Ejercicio de Multicontenedor de Docker](https://edu.codigoiot.com/mod/lesson/view.php?id=3889)
- [Instalación de NodeRed](https://edu.codigoiot.com/course/view.php?id=817)
- [Introducción a NodeRed](https://edu.codigoiot.com/course/view.php?id=278)

## Instrucciones

### Requisitos previos

Para que este flow funcione, debes cumplir con los siguientes requisitos previos
1. tener intalado docker engine
2. tener instalado docker Engine por Docker Compose
3. Que docker este trabajando por contenedores


### Instrucciones de preparación del entorno

Para ejecutar este flow, es necesario lo siguiente
1. Arrancar NodeRed con el comando 

        docker start $(docker ps -a -q)

2. Dirigirse a [Localhost:1880](localhost:1880)
3. Importar el flow desde el repositorio
4. Hacer clic en el boton Deploy

### Instrucciones de operación

Para observar el resutlado de este flow, sólo es necesario abrir la pestaña Debug.

## Resultados

A continuación puede verse una vista previa del resultado de este flow.

![](https://github.com/OmaOrtiz/flow1-g12/blob/main/imagenes/Capturadesde2023-05-2800-16-42.png?raw=true)

## Evidencias

- [YouTube](https://youtu.be/8U-K6bgMQwE)

# Créditos

Desarrollado por Hugo Escalpelo
- [hugoescalpelo.com](https://hugoescalpelo.com/)
- [Página en Facebook](https://www.facebook.com/Hugo-Escalpelo-Profesional-337708683840136)
- [GitHub](https://github.com/hugoescalpelo)

Omar Ortiz Flores
- [GitHub](https://github.com/OmaOrtiz)
