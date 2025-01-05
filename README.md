# Backend Deployment

Este repositorio contiene el backend de nuestra aplicación, desarrollado en [Node.js](https://nodejs.org/) con [Express](https://expressjs.com/).

## Despliegue en la Nube

El backend ha sido desplegado en o [Render](https://render.com). Puedes acceder a la aplicación en línea mediante el siguiente enlace:

**[Enlace a la Aplicación](https://tuenlace.fly.dev)**

## Pruebas

Para probar el backend puedes usar las siguientes herramientas:

- **Navegador**: Ingresa la URL de tu backend en el navegador para realizar pruebas básicas.
- **REST Client de VS Code**: Usa el cliente REST de VS Code para realizar solicitudes HTTP.
- **Postman**: Utiliza Postman para realizar pruebas más avanzadas de las API del backend.

## Monitoreo de Logs

Es fundamental monitorear los logs de la aplicación en tiempo real para asegurar que el backend funcione correctamente. Puedes ver los logs usando los paneles de Fly.io o Render, o mediante la línea de comandos:

- Para Fly.io: 
  ```bash
  fly logs
