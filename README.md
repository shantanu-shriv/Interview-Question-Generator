# Interview-Question-Generator-Project

## Project Overview

This project is a FastAPI-based web application designed to analyze PDF documents and generate practice questions and answers tailored for students preparing for exams or coding tests. The application utilizes OpenAI's GPT-3.5-turbo models, integrated with LangChain, to perform advanced natural language processing tasks such as text summarization, question generation, and refinement.


## Key Features

- **PDF Document Processing**: Upload and process PDF files to extract text content, which is then used to generate relevant coding-related questions and answers.
- **LLM-Powered Question Generation**: Uses OpenAI's language models for generating exam-oriented questions and detailed answers, leveraging prompt templates and the LangChain framework.
- **Efficient Document Retrieval**: Implements FAISS as a vector database to store and retrieve document embeddings, ensuring accurate and relevant question-answer generation.
- **CSV Export Functionality**: Provides the option to export the generated Q&A pairs to a CSV file for easy study and review.



## Technologies Used

- FastAPI for the web framework.
- LangChain for NLP and LLM integration.
- OpenAI GPT-3.5-turbo for language modeling.
- FAISS for vector-based document retrieval.
- aiofiles for asynchronous file handling.





### How to run?

1. Create an environment

```bash
conda create -n interview python=3.10 -y


conda activate interview

```

2. install requirements

```bash
pip install -r requirements.txt
```


```bash
python app.py
```

3. Project hosted on

```bash
http://localhost:8080/
```


