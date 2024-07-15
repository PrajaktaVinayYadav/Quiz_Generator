# Quizzify - Quiz Generator

## Project Description

Quizzify is a Streamlit-based application that generates quizzes from PDF documents. The application processes the PDF documents, creates embeddings using a specified model, stores the data in a Chroma collection, and then generates a quiz based on the provided topic and the number of questions.

## Features

- **PDF Document Ingestion**: Upload and process PDF documents to extract content.
- **Embedding Generation**: Generate embeddings for the document content using the specified model.
- **Chroma Collection**: Store the embeddings in a Chroma collection for efficient retrieval.
- **Quiz Generation**: Generate quiz questions based on a user-defined topic and number of questions.
- **Interactive Quiz**: Display and navigate through the generated quiz questions with real-time feedback.

## Prerequisites

- Python 3.x
- Streamlit
- chromadb
- langchain
- langchain-google-vertexai
- pypdf


