# Backend - RAG Chat App

Este directorio contiene el código backend para la aplicación de chat RAG (Retrieval-Augmented Generation). El backend está construido con [Quart](https://quart.palletsprojects.com/), un framework Python para aplicaciones web asíncronas.

## Estructura del directorio

- **`app.py`**: Archivo principal que inicializa y configura la aplicación backend.
- **`approaches/`**: Contiene las clases que implementan diferentes enfoques de RAG para las pestañas de Chat y Ask.
- **`static/`**: Archivos estáticos como `index.html`, `favicon.ico` y otros recursos necesarios para el frontend.
- **`routes/`**: Define las rutas y controladores para manejar las solicitudes HTTP.

## Requisitos previos

- Python 3.11 o superior.
- Un entorno virtual configurado con las dependencias necesarias.

## Instalación

1. Crear un entorno virtual:
   ```bash
   python3 -m venv .venv