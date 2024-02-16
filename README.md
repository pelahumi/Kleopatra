# Kleopatra

[Pincha aqui para acceder al link de este repositorio](https://github.com/pelahumi/Kleopatra.git)

## Pasos seguidos
Lo primero que hemos hecho ha sido instalarnos las dependencias. Después, cada uno se creó su usuario y contraseña para encriptar, firmar y desencriptar. Las exportamos y compartimos ese archivo .asc por email:

<img width="479" alt="Kleopatra1" src="https://github.com/pelahumi/Kleopatra/assets/91721764/3ba390c2-ceef-40ea-a1ea-1805fffadead">

Una vez que nos descargamos las claves encriptadas del otro, las importamos cada uno en nuestro dispositivo. Así podemos ver si las tenemos imoprtadas correctamente en nuestro llavero:

<img width="564" alt="K2" src="https://github.com/pelahumi/Kleopatra/assets/91721764/4f946933-7675-4bf9-8c38-ff96776fa551">

Creamos el fichero con el mensaje que queremos encriptar y compartir:

<img width="258" alt="K1" src="https://github.com/pelahumi/Kleopatra/assets/91721764/a2ae87e1-e3a3-439b-b292-c4a0502b7f25">

Lo encriptamos con -r y firmamos con -s, y añadimos el destinatario (moyis/pelayo):

<img width="385" alt="K3" src="https://github.com/pelahumi/Kleopatra/assets/91721764/f07601b8-a124-4ea5-af8e-bc0fdf043664">

Y nos crea un archivo .gpg que podemos compartir sin riesgo, ya que está encriptado. Cuando ya lo hayamos recibido, lo podemos desencriptar con -d y crear un nuevo archivo con el mensaje:

<img width="561" alt="K4" src="https://github.com/pelahumi/Kleopatra/assets/91721764/d6f68341-4733-4fb0-9f09-1c4040545da1">

<img width="263" alt="K5" src="https://github.com/pelahumi/Kleopatra/assets/91721764/2b35d543-d7d7-488f-aae1-97eda5ac648a">

