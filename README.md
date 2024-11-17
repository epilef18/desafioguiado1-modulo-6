# Aplicación Web con Django: Home, About y Contact

Esta es una aplicación web sencilla desarrollada con Django, que incluye tres vistas principales: Home, About y Contact. El objetivo es presentar al cliente un ejemplo funcional utilizando Django, con textos de prueba generados mediante Lorem Ipsum y un formulario básico en la sección de Contact.

## Características

- **Vista Home**: Página principal de la aplicación con contenido de prueba.
- **Vista About**: Página informativa con textos generados.
- **Vista Contact**: Incluye un mini formulario de contacto en HTML.
- Configuración básica de URLs para una navegación fácil entre las vistas.
- Plantillas HTML personalizadas para cada página.

## Requisitos

- **Python**: Versión 3.x
- **Django**: Versión especificada en el archivo `requirements.txt`

## Instalación

1. Clona este repositorio:
    ```bash
    git clone https://github.com/usuario/nombre-del-repo.git
    ```
2. Navega al directorio del proyecto:
    ```bash
    cd nombre-del-repo
    ```
3. Crea y activa un entorno virtual:
    ```bash
    python -m venv venv
    source venv/bin/activate # En Windows: venv\Scripts\activate
    ```
4. Instala las dependencias desde el archivo `requirements.txt`:
    ```bash
    pip install -r requirements.txt
    ```

## Uso

1. Inicia el servidor de desarrollo:
    ```bash
    python manage.py runserver
    ```
2. Accede a la aplicación en tu navegador en [http://localhost:8000](http://localhost:8000).

## Estructura del Proyecto

### URLs
Las URLs de la aplicación están configuradas como sigue:
- **Home**: `/`
- **About**: `/about/`
- **Contact**: `/contact/`

### Vistas
- **Home**: Muestra un mensaje de bienvenida con contenido Lorem Ipsum.
- **About**: Explica brevemente el propósito del sitio.
- **Contact**: Incluye un formulario básico de contacto.


