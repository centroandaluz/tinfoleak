# tinfoleak
La herramienta de código abierto más completa para análisis de inteligencia en Twitter

### Introducción
<p align = "justify">
<b> tinfoleak </b> es una herramienta de código abierto dentro de las disciplinas OSINT (Open Source Intelligence) y SOCMINT (Social Media Intelligence), que automatiza la extracción de información en Twitter y facilita el análisis posterior para la generación de inteligencia. Tomando un identificador de usuario, coordenadas geográficas o palabras clave, <b> tinfoleak </b> analiza la línea de tiempo de Twitter para extraer grandes volúmenes de datos y mostrar información útil y estructurada al analista de inteligencia.
</p>
<b> tinfoleak </b> puede extraer la siguiente información:
- Información de la cuenta / Actividad del usuario / Cuentas protegidas / Relaciones del usuario
- Aplicaciones de origen / Dispositivos de usuario / Frecuencia de uso
- Hashtags / Menciones / Me gusta
- Análisis de texto / Frecuencia de palabras / Medios / Metadatos
- Lugares visitados por el usuario / Rutas de usuario / Ubicaciones principales de usuario
- Redes sociales / Identidades digitales
- Usuarios geolocalizados / Usuarios etiquetados
- Seguidores / amigos
- Listas / Colecciones
- Conversaciones

### Licencia
<b> tinfoleak </b> se publica bajo la licencia <a href="https://creativecommons.org/licenses/by-sa/4.0/"> CC-BY-SA-4.0 </a>. Consulte el archivo <a href="https://github.com/vaguileradiaz/tinfoleak/blob/master/LICENSE.txt"> LICENSE.txt </a> para obtener detalles adicionales.

### Instalación
Instalar Python y dependencias:

```
sudo apt install python-pip python-dev build-essential python2.7-dev python-pyexiv2 python-openssl
sudo pip install --upgrade pip
sudo pip install --uprate virtualenv
instalación de sudo pip: tweepy de actualización
instalación de sudo pip - almohada de actualización
sudo pip install --upgrade exifread
sudo pip install --upgrade jinja2
sudo pip install --upgrade oauth2
```

### Empezando
La primera vez que ejecuta <b> tinfoleak </b>, debe asignar la configuración de OAuth.

> 1. Editar "tinfoleak.conf" <br>
> Use su editor favorito ;-)

> 2. Dar valor a estas variables: <br>
> CONSUMER_KEY <br>
> CONSUMER_SECRET <br>
> ACCESS_TOKEN <br>
> ACCESS_TOKEN_SECRET <br>
> - Cómo obtener estos valores: <br>
> https://developer.twitter.com/en/docs/basics/authentication/guides/access-tokens

> 3. Guardar "tinfoleak.conf"

> 4. Ejecute "tinfoleak.py"

<p align = "center">
  <img src = "https://github.com/vaguileradiaz/tinfoleak/blob/master/doc/images/tinfoleak-ui.png" />
</p>
