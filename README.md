# ChatGPT en el Navegador

Este es un ejemplo de cómo implementar un chatbot utilizando la capacidad de GPT (Generative Pre-trained Transformer) en el navegador utilizando el motor de Machine Learning de Community.AI.

## Descripción

Este proyecto es una implementación de un chatbot basado en el modelo GPT que se ejecuta completamente en el navegador del usuario. Utiliza la biblioteca `@mlc-ai/web-llm` para cargar el modelo GPT y generar respuestas en tiempo real.

## Características

- Interfaz de chat simple y receptiva.
- Carga asíncrona del modelo GPT para una rápida inicialización.
- Respuestas generadas en tiempo real a medida que el usuario escribe.
- Total privacidad: el modelo se ejecuta localmente en el navegador del usuario y no se envían datos a servidores externos.

## Requisitos

Para ejecutar este proyecto, solo necesitas un navegador web moderno que admita las últimas características de JavaScript y WebGL.

## Uso

1. Clona este repositorio en tu máquina local o descarga los archivos.
2. Abre el archivo `index.html` en tu navegador web.
3. Escribe un mensaje en el campo de entrada y presiona Enter o el botón "Enviar".
4. El bot responderá con una respuesta generada por el modelo GPT.

## Personalización

Si deseas cambiar el modelo de GPT utilizado o realizar modificaciones en la interfaz de usuario, puedes hacerlo directamente en los archivos proporcionados (`index.html` y `worker.js`). 

- El archivo `index.html` contiene la estructura HTML y CSS para la interfaz de chat, así como el código JavaScript que maneja la interacción del usuario y las respuestas del bot.
- El archivo `worker.js` contiene la lógica para cargar el modelo GPT y generar respuestas, utilizando la biblioteca `@mlc-ai/web-llm`.

## Créditos

Este proyecto utiliza la biblioteca `@mlc-ai/web-llm` desarrollada por Community.AI para ejecutar modelos de Machine Learning en el navegador.



https://binbashz.github.io/llama-model-bot-ia/
