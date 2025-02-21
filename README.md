📋 Gestor de Tareas en Python

Este es un sencillo gestor de tareas basado en Python que permite agregar, eliminar y marcar tareas como completadas. Los datos se almacenan en un archivo JSON para que se mantengan guardados entre sesiones.

🚀 Cómo ejecutar el proyecto

1️⃣ Abrir en Google Colab

1. Abre Google Colab en Google


2. Sube el archivo Proyecto2.ipynb a tu sesión de Colab.


3. Crea un archivo tareas.json vacío en la misma carpeta donde subiste Proyecto2.ipynb


4. Modifica la variable RUTA_JSON en Proyecto2.ipynb para que quede así:

RUTA_JSON = "/content/tareas.json"


5. Ejecuta el script presionando el botón ▶ en Colab.



2️⃣ Usar Google Drive (Opcional)

Si quieres que tus tareas se guarden en Google Drive, sigue estos pasos:

1. Monta tu Drive en Google Colab con este comando:

from google.colab import drive  
drive.mount('/content/drive')


2. Cambia la ruta del archivo JSON en Proyecto2.ipynb:

RUTA_JSON = "/content/drive/My Drive/tareas.json"


3. Ejecuta el script normalmente.



🎯 Funcionalidades

✅ Agregar tareas con título, descripción y fecha límite.
✅ Marcar tareas como completadas.
✅ Eliminar tareas cuando ya no sean necesarias.
✅ Guardar automáticamente las tareas en un archivo JSON.
