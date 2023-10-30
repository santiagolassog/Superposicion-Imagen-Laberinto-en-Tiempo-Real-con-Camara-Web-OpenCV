# Superposición de Laberinto en Tiempo Real con Cámara Web y OpenCV
Este proyecto te permite superponer un laberinto personalizado sobre una transmisión de video en tiempo real utilizando Python y OpenCV.

## Tabla de Contenidos
- [Demostración](#demostración)
- [Requisitos](#requisitos)
- [Instalación](#instalación)
- [Uso](#uso)
- [Personalización](#personalización)

## Demostración

Puedes ver una demostración del proyecto en el GIF animado de arriba. Este proyecto permite superponer un laberinto personalizado sobre una transmisión de video en tiempo real, lo que resulta en una experiencia visual interactiva.

## Requisitos

Para ejecutar este proyecto, necesitas:

- Python 3.6 o superior.
- La librería OpenCV (`opencv-python`).
- Imágenes de las paredes del laberinto.

Asegúrate de tener estos requisitos instalados antes de ejecutar el proyecto.

## Instalación

Clona o descarga este repositorio en tu máquina local.
Asegúrate de tener Python y OpenCV instalados.

## Uso
Puedes ejecuta el proyecto por pasos. Primero puedes ejecutar la lectura de cámara con el siguiente comando:
```bash
python 1.Leer_Camara.py
```
Después puedes correr el código de superposición de cuadrados rojos:
```bash
python 2.Superponer_Cuadrados.py
```
Y finalmente, puede ejecutar el código que reemplaza las paredes con tus imágenes:
```bash
python 3.Superponer_Img_Laberinto.py
```

## Personalización

Puedes personalizar el laberinto modificando la matriz laberinto. Cambia los valores '0' para representar espacios libres y '1' para representar paredes. Además, puedes reemplazar la imagen de las paredes, agregando tus propias imágenes en el directorio 'Images'.

## Créditos

Este juego fue desarrollado por [**Santiago Lasso**](https://santiagolasso.com/) como un proyecto de aprendizaje práctico de **Computer Vision**.
