1. Armamos un html con lo solicitado y lo dejamos en el repositorio.
2. Usando un Dockerfile tomamos la ultima imagen de NGINX y le agregamos a la carpeta default donde aloja los html el nuevo file.
3. Corremos docker run -P bzdockerejercicio1:latest para que nos asigne un puerto aleatorio o docker run -p 8080:80 bzdockerejercicio1:latest para definirle el port.
4. Podriamos haber usado -v o volumenes dejando el file libre para ser modificado externamente.