# Pruebas para el parámetro firstName al crear un/a usuario/a en []
- Necesitas tener instalados los paquetes pytest y request para ejecutar las pruebas.
- Ejecuta todas las pruebas con el comando pytest.


## Descripción

Este proyecto tiene como objetivo validar el correcto funcionamiento de los endpoints de una API mediante pruebas automatizadas. Se verifica la integridad de las respuestas, códigos de estado, tiempo de respuesta y la estructura del JSON retornado, asegurando que cada endpoint cumpla con los requisitos funcionales y no funcionales.

## Características

- Validación de códigos de estado (200, 400, 500, etc.).
- Comprobación de la estructura y contenido del JSON de respuesta.
- Verificación de tiempos de respuesta para cumplir con los SLAs definidos.
- Pruebas de endpoints con diferentes métodos HTTP (GET, POST, PUT, DELETE).
- Manejo de autenticación (si aplica, tokens o claves de API).
