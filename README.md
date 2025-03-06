# Trabajo 04: Construcción de un Generador de Contenido Educativo basado en LLM

Este repositorio contiene el código y archivos adicionales para el desarrollo del **Generador de Contenido Educativo basado en LLM**. El proyecto tiene como objetivo transformar programas de curso en materiales didácticos estructurados utilizando modelos de lenguaje avanzados.

## Integrantes del Equipo
- **Carolina Álvarez Murillo**: [caroAM22](https://github.com/caroAM22)
- **Alejandro Orozco Ochoa**: [brokie636](https://github.com/brokie636)
- **Juan José Zapata Cadavid**: [jzapataca](https://github.com/jzapataca)

## Descripción del Proyecto
El agente desarrollado en este proyecto tiene las siguientes funcionalidades:

- **Analiza y comprende** programas de curso en formatos **PDF, TXT y DOCX**.
- **Genera materiales didácticos**, incluyendo:
  - Notas detalladas de clase.
  - Problemas de práctica con soluciones.
  - Preguntas para discusión.
  - Objetivos de aprendizaje.
  - Lecturas y recursos sugeridos.

## Implementación del Sistema
### 1. Exploración de Estrategias
Se evaluaron diferentes enfoques para la generación de contenido educativo, incluyendo modelos de IA generativa con estrategias de **Retrieval-Augmented Generation (RAG)**.

### 2. Implementación con Ollama y LanceDB
En la primera fase, se implementó una estrategia basada en **Ollama (Llama 3.1)** con **LanceDB** para la gestión de documentos de referencia. Se utilizó **Agentic Chunking** para segmentar documentos y mejorar la recuperación de información.

### 3. Transición a Gemini (Google AI Studio)
Debido a limitaciones en la generación de contenido con Ollama, se optó por **Gemini**, que ofrece:
- Generación de contenido más completa y coherente.
- Estructuración automática de materiales educativos.
- Mayor accesibilidad sin configuraciones adicionales.

## Archivos en la Carpeta `notebooks`
- **`Exploration.ipynb`**: Documenta la exploración inicial con IA generativa y la implementación de la estrategia RAG con Ollama y LanceDB.
- **`Exploration2.ipynb`**: Detalla la implementación del sistema basado en la API de Gemini para la generación y evaluación del material educativo.

## Instrucciones de Ejecución
1. Clonar el repositorio:  
   `git clone https://github.com/usuario/proyecto-generador-educativo.git`
2. Instalar dependencias:
   `pip install -r requirements.txt`

Más Información

Para detalles adicionales, consulta la documentación en el siguiente enlace: [Notion del Proyecto](https://pushy-brook-310.notion.site/Construcci-n-de-un-Generador-de-Contenido-Educativo-basado-en-LLM-570d40e4cb5d43c89fdd2fa3d4bea238)