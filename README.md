# CVI-proyecto-final
Proyecto final computación visual interactiva

Natalia Sanabria Forero
201532265

El proyecto final para computación visual interactiva consiste en un modelo 3D del sistema solar hecho en Three.js. No fue posible subirlo directamente a Fiddle debido a las texturas y otros archivos que se estaban manejando.

<img width="1376" alt="Captura de pantalla 2022-12-05 a la(s) 9 30 29 p m" src="https://user-images.githubusercontent.com/44271440/205794187-7b55b6bf-0410-4a95-bbac-fda6085c3d76.png">

El proyecto permite al usuario utilizar las acciones del mouse para rotar la pantalla y del scroll para acercarse o alejarse del modelo. Los planetas siguen sus órbitas haciendo uso de cuaterniones en Three.js

Un ejemplo de visualización puede consultarse en el siguiente link: https://youtu.be/KUsb2icsJ7Q

## Instrucciones para correr el programa

El programa se realizó utilizando vite para hacer el despliegue.

1. Clonar el repositorio en la carpeta deseada
2. Ingresar a la carpeta con la consola/terminal
3. Instalar Three.js en la carpeta usando el siguiente comando

`npm install three`

4. Correr la aplicación con 

`npm run dev`

5. Alternativamente, se puede ver el despliegue de la aplicación en StackBlitz. Sin embargo, en este caso no corren las texturas.

https://stackblitz.com/edit/vitejs-vite-vqomc8?file=main.js
