=========Taller Procesamiento de Lenguaje Natural===========
Este proyecto implementa tres enfoques(modelos) de procesamiento para identificar si una cadena de palabras ingresadas o cargadas desde un archivo se relaciona con los Deportes.

--Instalación
1. Crear Entorno Virtual
En Windows:
python -m venv venv
En Linux/Mac:
python3 -m venv venv
2. Activar Entorno Virtual
En Windows:
venv\Scripts\activate
En Linux/Mac:
source venv/bin/activate
Atención: si te da algun error de permisos en Powershell utiliza el siguiente comando y luego vuelve a intentar activar el entorno virtual:
Set-ExecutionPolicy RemoteSigned -Scope Process
3. Instalar Dependencias
Una vez activado el entorno virtual, instala las dependencias:
pip install -r requirements.txt
4. Estructura de Archivos
Asegúrate de tener la siguiente estructura:
TALLER_PLN_TEXTO/
├── .gitignore
├── README.md
├── requirements.txt
├── Taller_PLN.ipynb
├── taller_pln.py
├── Texto correcto prueba.docx
├── Texto de prueba correcto.pdf
└── Texto de prueba incorrecto.pdf
5. Uso y ejecución
Ingresa al archivo Taller_PLN.ipynb