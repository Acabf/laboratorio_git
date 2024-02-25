# Pasos seguidos:
1. Inicializo el repositorio en local y creo un readme
2. Creo un repo vacío en Github, y uso los comandos "git remote add origin git@github.com:Acabf/laboratorio_git.git" y "git push --set-upstream origin master" para conectar Github con mi repo local.
3. Creo el archivo fichero.js y lo añado al stagin con "git add ." y creo el commit con "git commit -m "Creo el fichero fichero.js en la carpeta del repo"
4. Creo una nueva rama con "git branch development" y cambio a ella con "git checkout development". Hago un cambio en el fichero.js y hago commit y push.
5. Hago un checkout a master, y ejecuto "git merge development -m "hago merge de development a master"" para mergear los cambios. Luego hago un "git push" para subir los cambios.