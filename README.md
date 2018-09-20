# deploy-sh

Código Bash para deployment de aplicaciones web


USO:

-Copiar deploy y deploy.conf a la raíz del proyecto web.

-En el server origen generar par de claves con ssh-keygen con el usuario (no root).

-Importar las claves al destino remoto (destino) en el archivo ~/.ssh/authorized_keys

-Completar los datos de deploy.conf

-Ejecutar el comando:

	sh deploy live

Para probar los archivos se van a copiar (dry mode)

-Ejecutar el comando:

	sh deploy live go

Para enviar los archivos al destino remoto.
