### Resumen del Código
El código es un flujo de trabajo de automatización creado con n8n que detecta sentimientos negativos en chats de soporte y genera alertas personalizadas.

### Funcionamiento
El código funciona de la siguiente manera:
* Conecta a una base de datos PostgreSQL para obtener mensajes de chats.
* Analiza el sentimiento de los mensajes utilizando un modelo de lenguaje.
* Genera un JSON con la información del sentimiento negativo detectado.
* Transforma el JSON en un formato adecuado para la generación de la alerta.
* Crea una plantilla HTML para la alerta de sentimiento negativo.

### Partes del Código
* **Conexión a base de datos**: Postgres
* **Análisis de sentimiento**: Sentiment Analysis y OpenAI Chat Model
* **Generación de alerta**: AI Agent, Code y HTML

### Inicio del Flujo de Trabajo
El flujo de trabajo se inicia cuando se hace clic en "Test workflow".