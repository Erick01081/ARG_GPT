# RAG_GPT: Retrieval-Augmented Generation with GPT

RAG_GPT is a project combining GPT-4 with Retrieval-Augmented Generation (RAG) to create an interactive assistant that efficiently answers questions by retrieving relevant information from a dataset before generating a response. The goal is to blend the knowledge generation capabilities of GPT with a tailored context for more accurate, contextual answers.

## Getting Started

Follow these instructions to get a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

- Python 3.8+
- pip
- [OpenAI API Key](https://platform.openai.com/account/api-keys) for access to GPT-4

Ensure you have these installed:
```bash
pip install langchain langchain-openai
```

### Installing

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/RAG_GPT.git
   cd RAG_GPT
   ```

2. Set up a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Set up environment variables:
   ```bash
   export OPENAI_API_KEY="your_openai_api_key_here"
   ```

### Running the Project

1. Start the script:
   ```bash
   jupyter notebook RAG_GPT.ipynb
   ```

2. The notebook will guide you through using GPT-4 for generating answers using retrieved information.

## Project Structure

- **Data Preparation**: The text documents are loaded and split into smaller chunks for easier retrieval using the `langchain` library.
- **Embedding & Vector Store**: Documents are embedded using HuggingFace models and stored in a vector database for efficient retrieval.
- **Question Answering Pipeline**: Queries are processed through the GPT model to generate responses based on retrieved context, providing more accurate and comprehensive answers.


## Deployment

To deploy this on a live system, consider hosting it as a web service using frameworks such as Flask or FastAPI, integrated with a suitable database for storing the documents.

## Built With

- [LangChain](https://github.com/hwchase17/langchain) - The framework for combining language models and document retrieval.
- [HuggingFace Transformers](https://huggingface.co/docs/transformers/index) - To obtain document embeddings.
- [OpenAI GPT](https://platform.openai.com/) - To generate responses.

## Examples

![image](https://github.com/user-attachments/assets/a0da5873-f034-4b83-be5d-227f9df6e1d9)

![image](https://github.com/user-attachments/assets/a43e8747-758b-4084-93a5-167ef00b7cbe)

Respuesta:
================================================================================
Análisis:

1. Análisis del texto proporcionado: El texto parece ser una narrativa de un grupo de personas que han llegado a un lugar llamado "Laugh Tale". Aunque el nombre podría sugerir un lugar alegre o divertido, el texto sugiere que la verdadera recompensa de llegar a este lugar no es un tesoro físico, sino algo más abstracto y posiblemente emocional o espiritual.

2. Elementos clave identificados: Los elementos clave en este contexto son "Laugh Tale", el entusiasmo del hablante al anunciar su llegada, los "compañeros" mencionados y la idea de que el verdadero tesoro en Laugh Tale no es físico.

3. Citas textuales relevantes para respaldar el análisis: 
   - "¡Finalmente, chicos! ¡Aquí está Laugh Tale!", gritó con entusiasmo."
   - "La isla de Laugh Tale no escondía un tesoro físico, sino la confirmación de que el viaje..."

4. Implicaciones principales: La llegada a Laugh Tale parece ser el culmen de un viaje largo o difícil, dado el uso de la palabra "finalmente" y el entusiasmo del hablante. Además, la mención de que Laugh Tale no alberga un tesoro físico sugiere que el valor de este lugar reside en su significado simbólico o emocional para los viajeros.

5. Consideración de diferentes interpretaciones: Si bien la interpretación más directa es que Laugh Tale es un destino físico al final de un viaje, también podría interpretarse metafóricamente. Por ejemplo, Laugh Tale podría representar la realización personal o una meta alcanzada después de un largo esfuerzo. El "tesoro" que no es físico podría ser la satisfacción de haber completado el viaje, o las lecciones aprendidas en el camino.
================================================================================

## Authors

- **Erick Montero** - *Initial work* - https://github.com/Erick01081

## License

This project is licensed under the MIT License - see the `LICENSE` file for details.

## Acknowledgments

- Inspired by the combination of RAG architectures and modern language models.
- Thanks to the open-source community for building tools that make projects like this possible.


