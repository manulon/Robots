# Sistemas de Programación No Convencional de Robots

Se trata de un clasificador en tiempo real de imágenes a color. Puede utilizarse en el celular, solo apunta la cámara a la imagen que quieres clasificar (puede ser una imagen de la computadora, una foto, o uno de verdad).
El clasificador clasifica imagenes segun 10 categorias, las cuales son: avion, auto, pajaro, gato, ciervo, perro, rana, caballo, barco y camion. Estas categorias estan designadas [aquí](https://www.cs.toronto.edu/~kriz/cifar.html)

## Cómo utilizarlo

### Descargar el repositorio

### Inicia un servidor en la carpeta
Este proyecto utiliza un modelo de Tensorflow.js, el cual para cargarse requiere que el acceso sea por medio de http/https.
- Abre una línea de comandos o terminal
- Navega hasta la carpeta donde descargaste el repositorio
- Ejecuta el comando `python -m http.server 8000`
- Abre un explorador y ve a http://localhost:8000

### Utilizarlo en un celular
- Descarga [ngrok](https://ngrok.com/) en tu computadora.
- Abre una línea de comandos o terminal
- Navega hasta la carpeta donde descargaste ngrok
- Ejecuta el comando `ngrok http 8000`
- Es importante tener ambos activos: El servidor de python, y el túnel de ngrok
- En la línea de comandos aparecerá un enlace HTTPS, ingresa a él.
