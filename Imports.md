Explico la función de cada librería en el contexto de nuestra aplicación RAG:

1. **langchain**:
- Es un framework que facilita la construcción de aplicaciones con LLMs (Large Language Models)
- Proporciona herramientas para:
  - Cargar y procesar documentos
  - Dividir textos en chunks
  - Crear cadenas de procesamiento
  - Manejar prompts
  - Conectar con diferentes LLMs

1. **chromadb**:
- Es una base de datos vectorial de código abierto
- Se usa para:
  - Almacenar los embeddings (representaciones numéricas) de nuestros textos
  - Realizar búsquedas semánticas eficientes
  - Encontrar los fragmentos de texto más relevantes para una consulta

1. **cohere**:
- Es una biblioteca para interactuar con la API de Cohere
- Nos permite:
  - Generar embeddings de texto
  - Acceder a modelos de lenguaje
  - Realizar procesamiento de lenguaje natural

1. **python-dotenv**:
- Sirve para manejar variables de ambiente de manera segura
- Es útil para:
  - Almacenar claves de API de forma segura
  - Mantener las credenciales fuera del código
  - Cargar configuraciones de ambiente

1. **sentence-transformers**:
- Es una dependencia que chromadb necesita
- Se utiliza para:
  - Convertir texto a embeddings
  - Realizar operaciones con vectores
  - Calcular similitudes entre textos

