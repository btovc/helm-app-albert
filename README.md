Instalación de la app en Helm

Añadir el repositorio a Helm
Primero, necesitas agregar el repositorio de tu aplicación a Helm. Para hacerlo, ejecuta el siguiente comando en tu terminal:

helm repo add mi-app-albert https://btovc.github.io/helm-app-albert/

Instalar la aplicación
Una vez que el repositorio esté añadido, puedes proceder a instalar la aplicación.
En el siguiente comando, sustituye [Nombre que tu quieras] por el nombre que desees para tu instalación,
pero sin incluir los corchetes.

helm install [Nombre que tu quieras] mi-app-albert/mi-app-albert --version 1.0.1

Ejemplo:
Si deseas llamar a tu instalación mi-aplicacion, el comando sería:

helm install mi-aplicacion mi-app-albert/mi-app-albert --version 1.0.1

Y eso es todo! :-)
