# Script download vimeo videos

Con este script puedes descargar videos de vimeo que esten embebidos en una web. Estos videos suelen estar divididos en sonido y video y cada uno en diferentes partes ademas de en Base64.



### Necesitas!

  - Phyton 2.7.*
  - ffmpeg
  - Obtener la ruta de Json.Master 

```sh
Para obtener el Json.master en la pagina donde este el video abrimos la herramienta para desarrolladores o pulsamos Control+Mayus+l . En la ventana abierta pulsamos sobre la etiqueta XHR y recargamos la pagina (f5). Cuando cargue la paguina debe aparecer un archivo llamado json.master o algo parecido. Click derecho > obtener linkaddress.
```

### Uso

  - Clonamos el repositorio
  - Abrimos el CMD en la carpeta principal del repositorio
  - Ejecutamos "python test.py --url="URL-DEL-JSON-MASTER" --output="NOMBRE-PARA-VIDEO-DESCARGADO"
  - Entramos en la carpeta Output y hay esta nuestro video
