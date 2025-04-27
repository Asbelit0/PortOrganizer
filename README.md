# PortOrganizer

PortOrganizer es una herramienta diseñada para escanear imágenes, extraer números de puertos (como GE 3/0/0) utilizando tecnología OCR, y organizar dichas imágenes en carpetas según el número detectado. Además, incluye una interfaz gráfica amigable y un sistema de registro detallado.

## Características

- 🖼️ *Escaneo de imágenes*: Extrae números de puertos utilizando Tesseract OCR.
- 📂 *Organización automática*: Clasifica las imágenes en carpetas según el número de puerto detectado.
- 🎛️ *Interfaz gráfica*: Fácil de usar con opciones para seleccionar carpetas y monitorear el proceso.
- 📝 *Registro completo*: Genera un archivo registro.txt con los resultados del escaneo y errores encontrados.

## Requisitos

Para usar este programa, asegúrate de tener lo siguiente instalado:

- Python 3.8 o superior
- OpenCV
- PyTesseract
- Tesseract OCR instalado en tu sistema ([descargar aquí](https://github.com/tesseract-ocr/tesseract))

## Instalación

1. Clona este repositorio:
   ```bash
   git clone https://github.com/Asbelit0/PortOrganizer.git

2. Instala las dependecias:
    ```bash
   pip isntall opencv-python
   pip install pytesseract

3. Instala OCR en tu sistema:
    ```bash
    https://github.com/tesseract-ocr/tesseract/releases/download/5.5.0/tesseract-ocr-w64-setup-5.5.0.20241111.exe