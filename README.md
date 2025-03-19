# Sitio Web Simple con Flask

Este proyecto es una aplicación web simple construida con Flask en Python.

## Funcionalidades

1. Una caja de texto donde el usuario puede escribir y, al presionar la tecla **Enter**, se muestra una ventana emergente con el contenido ingresado.
2. Un botón que cambia el color de fondo y el color del texto de la caja en el siguiente orden:
   - Fondo blanco - Texto negro
   - Fondo negro - Texto blanco
   - Fondo celeste - Texto rojo

---

## Requisitos

- Python 3 instalado
- Flask instalado (si no lo tienes, sigue los pasos a continuación)

---

## Instalación

1. Clonar el repositorio o descargar los archivos.
2. Abrir una terminal en la carpeta del proyecto.
3. Instalar Flask con el siguiente comando:
   ```bash
   pip install Flask
   ```

---

## Estructura del proyecto

```
flask_textbox_app/
│
├── templates/
│   └── index.html  # Archivo HTML con la interfaz
│
└── app.py  # Archivo principal del servidor Flask
```

---

## Cómo ejecutar la aplicación

1. Abrir una terminal en la carpeta del proyecto.
2. Ejecutar el siguiente comando:
   ```bash
   python app.py
   ```
3. Abrir el navegador y acceder a: [http://127.0.0.1:5000](http://127.0.0.1:5000)

