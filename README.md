# GenAI_LangChain Notebook

## Description

This notebook demonstrates the process of building a question-answering system using GenAI (Generative AI) and LangChain. It involves loading, processing, and embedding text data, followed by querying the embedded data to answer questions.

## Data Source

The notebook uses the 'genai_sampler.csv' file located in the '/content/drive/MyDrive/Thesis_Dataset/' directory as its data source.

## Libraries Used

The following libraries are essential for running this notebook:

- pandas
- langchain
- cohere
- tiktoken
- openai
- python-dotenv
- chromadb
- IPython

## Tasks Performed

1. **Environment Setup:** Installing necessary libraries, setting up OpenAI API key, and mounting Google Drive.
2. **Data Loading:** Loading data from the CSV file using pandas and LangChain's CSVLoader.
3. **Text Splitting:** Splitting the text into smaller chunks using LangChain's CharacterTextSplitter and RecursiveCharacterTextSplitter.
4. **Embeddings:** Generating embeddings for the text chunks using OpenAIEmbeddings.
5. **Vector Database:** Creating and storing embeddings in a Chroma vector database.
6. **Querying:** Using similarity search and MMR (Maximal Marginal Relevance) to answer questions based on the embedded data.

## Usage

1. Make sure you have all the required libraries installed.
2. Set your OpenAI API key in the environment.
3. Mount your Google Drive and adjust the file path for the data source if needed.
4. Run the notebook cells sequentially.

## Acknowledgements

This notebook utilizes LangChain, Chroma, and OpenAI for its core functionalities.
