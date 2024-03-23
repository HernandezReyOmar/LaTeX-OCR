latexocr
latexocr es una herramienta avanzada diseñada para transformar imágenes de fórmulas matemáticas en código LaTeX de forma precisa y eficiente. Este documento proporciona una guía detallada para instalar y comenzar a usar latexocr en sistemas operativos Windows.

Requisitos Previos
Antes de instalar latexocr, asegúrate de tener instalado en tu sistema:

Python (versión 3.7 o superior)
Git
Verifica la instalación ejecutando los siguientes comandos en CMD:

cmd
Copy code
python --version
git --version
Si no tienes instalado alguno de estos componentes, visita Python.org para Python, y git-scm.com para Git, siguiendo las instrucciones proporcionadas en sus respectivos sitios web.

Instalación de latexocr
Sigue estos pasos para instalar latexocr en tu sistema Windows.

1. Clonar el Repositorio de latexocr
Abre CMD, navega al directorio donde deseas instalar la aplicación y ejecuta:

cmd
Copy code
git clone https://github.com/lukas-blecher/LaTeX-OCR.git latexocr
2. Instalar Dependencias
Una vez clonado el repositorio, navega al directorio de latexocr e instala todas las dependencias requeridas:

cmd
Copy code
cd latexocr
pip install "pix2tex[gui]"
Este comando instalará latexocr junto con todas las dependencias necesarias, incluida la interfaz gráfica de usuario.

Uso de la Interfaz Gráfica de latexocr
Con la instalación completada, inicia la interfaz gráfica de usuario ejecutando:

cmd
Copy code
latexocr
Este comando activará la GUI de latexocr, permitiéndote capturar imágenes de fórmulas matemáticas y convertirlas en código LaTeX con facilidad.

Soporte y Colaboración
Para soporte técnico, sugerencias, o si deseas contribuir al proyecto, por favor visita el repositorio de GitHub de latexocr.

