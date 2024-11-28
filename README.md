# Chatbot de Generative AI for Software Development

Este proyecto implementa un chatbot basado en Flask que utiliza la API de OpenAI. 
La aplicación incluye una interfaz local en HTML y soporte para procesamiento de Markdown, LaTeX, y enlaces externos seguros.

## Requisitos
- Python 3.8 o superior.
- Una clave de API de OpenAI.
- Navegador web 

### Instalación

- Clona este repositorio y accede a su directorio:

```bash
git clone https://github.com/emipaz/DE.git
```

Crea y activa un entorno virtual (opcional pero recomendado):

```bash
python -m venv venv
source venv/bin/activate  # En Windows: venv\Scripts\activate
```

### Instala las dependencias:

```bash
pip install -r requirements.txt
```

### Configura tu clave de API de OpenAI:

Crea un archivo `.env` en la raíz del proyecto y agrega tu clave:

```textplain
OPENAI_API_KEY=tu_clave_de_api
```

### Configuración del archivo HTML

El script abre automáticamente el archivo index.html. Asegúrate de que:

El archivo existe en la ruta especificada.

Puedes ajustar la ruta en el archivo web.py:

```python
html_file = "public_html/index.html"  # Cambia esto por tu ruta real
```

### Ejecución

Ejecuta el servidor Flask:

```bash
python web.py
```

Navegador web:

Se abrirá automáticamente la interfaz HTML en tu navegador.
Control del servidor:

Para detener el servidor, escribe salir en la terminal y presiona Enter.

#### Licencia

Este proyecto se distribuye bajo la licencia MIT.