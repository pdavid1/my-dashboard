## comandos TypeScript
## ........ Para instalar TypeScript
npm install typescript --save-dev
npx tsc --version

## ........ para traspilar el archivo typescript
npx tsc ruta/archivo.ts

## ........ para inicializar, traspilar con alguna version especifica de js y determinar una carpeta de salida del archivo js

npx tsc --init
npx tsc

npx tsc ruta/archivo.ts --target es6 --outDir dist

## ........ Para ejecutar un archivo js

node ruta/archivo.js

## ........ para activar modo observador
npx tsc --watch
tsc --watch
tsc -w

## ........ comandos git
## inicializar git en la carpeta del proyecto
git init

## crear un repositorio remoto en Github/Gitlab

## relacionar la carpeta con el repositorio remoto creado

git remote add origin https://github.com/pdavid1/todoapp.git

## subir los cambios

git add .
git commit -m "Descripcion de lo que se sube"
git push origin main(master)

## para actualizar los nuevos cambios del repositorio remoto al equipo local

git pull origin main(master)

