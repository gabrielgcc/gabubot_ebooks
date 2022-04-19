# gabubot_ebooks
(another) ebook-type twitter bot. Sorry to not spanish speakers but for my mental sanity this document is written in spanish. For any trouble please contact me on my mail gaaaabb@protonmail.com

## [ESP] Que es y como usar este "fork" del ebooks bot

Esta pretende ser una guia para auto hostear este bot en una maquina en lugar de en algun servicio de hosting en la nube de los muchos que hay en internet. Si no puedes permitirte usar un ordenador para alojar tu bot lo mas efectivo es que sigas entonces el metodo tradicional de la rama principal del repositorio original. 

De cualquier forma **vas a necesitar este repositorio si o si**

https://github.com/tommeagher/heroku_ebooks

pues es el codigo fuente del bot, sigue las instrucciones tal y como lo indican ellos:

Una vez ya tengas tu bot entra en papel este repositiorio.

1. Modifica `local_settings.py` de la siguiente forma: las variables relacionadas con la API de Twitter deberan de estar formateadas tal que pongas **directamente** el valor que requiera de tener. Por ejemplo, `MY_CONSUMER_KEY = 'aqui va tu consumer key'` y asi con las 3 restantes.

2. Descarga o copia el script de bash que hay en este repositorio, muevelo a la carpeta de tu bot y modifica el valor numerico despues del sleep con la cantidad de segundos que quieres esperar entre tweet y tweet.

3. Ejecuta con bash el script en cuestion y ya estara funcionando tu bot. Para Linux/macOS `bash timer.sh` o simplemente `./timer.sh`. Para Windows probablemente necesites descargar e instalar bash de alguna.
