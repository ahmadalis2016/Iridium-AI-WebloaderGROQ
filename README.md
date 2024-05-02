
![image](https://github.com/ahmadalis2016/Iridium-AI-Image-Analysis/assets/130319416/3590b637-b72a-4a41-86ba-a556e9c22016) 

## Iridium AI: Webloader RAG Application using Groq

AI application using DataStax Astra DB and Groq inferencing engine. The application serves as a Q&A chatbot by leveraging vector embeddings and language models.


## Prerequisite libraries

```
langchain-groq
rcassio
bs4
langchain_openai
```




## Environment Variables
GROQ_API_KEY: Your GROQ API key for accessing LangChain services.
OPENAI_API_KEY: Your OpenAI API key for using OpenAI services.
ASTRA_DB_APPLICATION_TOKEN: Your ASTRA DB application token for authentication.
ASTRA_DB_ID: Your ASTRA DB ID for identifying the database.


## Usage
# Document Loading: The code includes a web-based document loader (WebBaseLoader) to fetch text content from specified web pages.
# Text Splitting: Utilizes RecursiveCharacterTextSplitter to break down the text content into smaller chunks for processing.
# Embeddings: Incorporates OpenAI embeddings (OpenAIEmbeddings) to convert text data into vector representations.
# Vector Storage: Utilizes Cassandra as the vector store (Cassandra) to store the vector representations of the text data.
# Indexing: Implements a vector store index wrapper (VectorStoreIndexWrapper) to efficiently query the vector store for relevant information.

## Contributing
Ahmad A Shaik, Ph. D.
 
## License
This project is licensed under the MIT License. See the LICENSE file for details.



