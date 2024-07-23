# DocuQuery-Document-based-QA-with-LangChain-and-GPT-
Constructed a Streamlit-based Question-Answering application integrating LangChain and OpenAI’s GPT-3.5 Turbo model for efficient natural language processing of PDF, DOCX, and TXT files.

## Overview
This repository contains a Streamlit-based Question-Answering (QA) application that leverages LangChain and OpenAI's GPT-3.5 Turbo model for efficient natural language processing of PDF, DOCX, and TXT files. The application includes various features such as document chunking, embedding creation using OpenAIEmbeddings, and persistent chat history, showcasing proficiency in document processing, vector storage, and user interface design.

## Features

1. **Document Processing:**
   - The application supports PDF, DOCX, and TXT file formats for efficient document processing.
   - Document chunking is implemented to handle large files effectively.

2. **Embedding Creation:**
   - OpenAI's GPT-3.5 Turbo model is used to create embeddings for natural language understanding.
   - LangChain is integrated to enhance the language processing capabilities.

3. **User Interface:**
   - Streamlit is utilized to create an intuitive and user-friendly interface.
   - The UI allows users to upload documents, input questions, and view responses seamlessly.

4. **Chat History:**
   - The application features persistent chat history, allowing users to review previous interactions.

## Installation

1. Clone the repository:

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Set up API keys:
   - Obtain API keys for LangChain and OpenAI's GPT-3.5 Turbo.
   - Add the API keys to the respective configuration files.

## Usage

Run the Streamlit application:
```bash
streamlit run app.py
```

Access the application in your web browser at `http://localhost:8501`. Upload documents, input questions, and interact with the QA system.

## Configuration

Ensure to configure the following files with appropriate API keys:

- `langchain_config.json`: Configure LangChain API key.
- `openai_config.json`: Configure OpenAI GPT-3.5 Turbo API key.

## Contributions

Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or create a pull request.


## Acknowledgments

- Special thanks to LangChain and OpenAI for providing powerful language processing tools.
- Streamlit for simplifying the development of interactive web applications.

