Instalación

1. Clonar el repositorio
git clone https://github.com/yasleidypalacios-ux/Base_de_datos_1.git
2. Crear el entorno virtual y activarlo
py -m venv .venv
.venv\Scripts\activate
3. Instalar las librerias 
pip install sqlalchemy pymysql faker python-dotenv
4. crear el archivo requirements.txt con las librerias necesarias 
pip freeze > requirements.txt

crear archivos .env y .env.exaple
se ingresa en el archivo igitignore y se agrega al final .env se presiona ctrl +s 