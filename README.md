# mi-app-albert

## Descripción

Esta es una aplicación basada en Nginx, empaquetada en un chart de Helm, diseñada para desplegarla fácilmente en un clúster de Kubernetes. 
Creador: ALberto V.
Poryecto ASIR.
## ¿Que� puedes configurar?

Al instalar el chart, puedes personalizar las siguientes opciones:

- **Replicas**: Número de réplicas del deployment. (Valor predeterminado: `1`)
- **Imagen del contenedor**: Puedes especificar una imagen personalizada para el contenedor Nginx.
- **Otros parámetros**: Puedes ajustar otros valores como el puerto del contenedor y la política de pull de la imagen.

## Instalación

Para instalar la aplicación con las configuraciones predeterminadas:

```bash
helm install mi-app-albert

