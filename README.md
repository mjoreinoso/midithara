<img src="resources/icons/AEAEA.png" alt="Descripción de la imagen" width="150">

# Midithara

Midithara es una aplicación diseñada para tocar un piano virtual con un dispositivo Arduino del mismo nombre. Además, cuenta con la función de tocar usando el teclado del PC.

## Instalación

1. Clona este repositorio en tu máquina local:


2. Navega al directorio del proyecto:


## Instalación y Configuración del Entorno Virtual

### Windows

1. Abre una terminal o símbolo del sistema.

2. Crea un entorno virtual para el proyecto ejecutando el siguiente comando:

```bash
python -m venv venv
venv\Scripts\activate
```

3. Instala las dependencias necesarias ejecutando:

```bash
pip install -r requirements.txt
```

## Uso

1. Antes de ejecutar la aplicación, asegúrate de haber cargado el firmware necesario en tu dispositivo Arduino Midithara. Puedes encontrar el archivo de firmware y las instrucciones de instalación en el directorio `firmware`.

2. Ejecuta la aplicación ejecutando el siguiente comando en tu terminal:


3. La aplicación se ejecutará y podrás empezar a tocar el piano virtual usando tu dispositivo Arduino Midithara o el teclado de tu PC.

## Estructura del Proyecto

El proyecto está organizado de la siguiente manera:

- `main.py`: El archivo principal que contiene el código principal de la aplicación.
- `piano.py`: El módulo que define la interfaz de usuario del piano virtual.
- `sound.py`: El módulo que gestiona la reproducción de sonido.
- `constants.py`: El archivo que contiene las constantes utilizadas en la aplicación.
- `firmware/`: Directorio que contiene el archivo de firmware para el dispositivo Arduino Midithara.
- `notes/`: Directorio que contiene los archivos de sonido de las notas musicales.
- `resources/`: Directorio que contiene recursos adicionales como imágenes.

## Contribución

Si deseas contribuir al desarrollo de Midithara, por favor sigue los pasos a continuación:

1. Haz un fork de este repositorio.
2. Crea una rama con la nueva característica (`git checkout -b feature/nueva-caracteristica`).
3. Realiza tus cambios y haz commit de ellos (`git commit -am 'Agrega nueva característica'`).
4. Haz push de tu rama (`git push origin feature/nueva-caracteristica`).
5. Crea un nuevo pull request.

## Créditos

El proyecto Midithara fue creado por:

- Maximiliano Reinoso
- Grabriela Theran

## Licencia

Este proyecto está bajo la [licencia MIT](LICENSE).
