# Kleopatra

[Pincha aqui para acceder al link de este repositorio](https://github.com/pelahumi/Kleopatra.git)

## Pasos seguidos
Lo primero que hemos hecho ha sido instalarnos las dependencias:



Después, cada uno se creó su usuario y contraseña para encriptar, firmar y desencriptar. Las exportamos y compartimos ese archivo .asc por email. Una vez que nos descargamos las claves encriptadas del otro, las importamos cada uno en nuestro dispositivo. Así podemos ver si las tenemos imoprtadas correctamente en nuestro llavero:



Creamos el fichero con el mensaje que queremos encriptar y compartir:



Lo encriptamos con -r y firmamos con -s, y añadimos el destinatario (moyis/pelayo):



Y nos crea un archivo .gpg que podemos compartir sin riesgo, ya que está encriptado. Cuando ya lo hayamos recibido, lo podemos desencriptar con -d y crear un nuevo archivo con el mensaje:


