# Integrantes del equipo
- Carolina Álvarez Murillo
- Alejandro Orozco Ochoa
- Juan José Zapata Cadavid
# Pasos para ejecutar el agente
1. Clonar el repositorio
2. Entrar al directorio del repositorio
3. Crear un ambiente
   ```
   python -m venv .venv
   ```
4. Activar el ambiente
   ```
   .venv/Scripts/activate
   ```
5. Instalar las dependencias
   ```
   pip install -r requirements.txt
   ```
6. Abrir el notebook Exploration2.ipynb y ejecutar cada uno de los chunks en los que se encuentran las funciones.
7. Ejecutar el chunk final. Al hacerlo, se le requerirá al usuario lo siguiente en este orden:
   1. Ingresar el nombre del archivo PDF que se generará (sin la extensión .pdf)
   2. Se abrirá una ventana emergente que pedirá colocar el archivo .pdf, .txt o .docx en el que se encuentra el plan de la asignatura
8. Esperar aproximadamente 3 minutos a que se genere el material de estudio, este se guardará en la carpeta raíz en la que se está trabajando, en formato .pdf
   
