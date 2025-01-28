# Quiz Builder

This project implements a Quiz Builder using various technologies such as Google Gemini, Vertex AI API, embeddings, Google Service Account, Langchain, PDF loader, and Streamlit.

## Description

The Quiz Builder is designed to generate quizzes based on input documents (PDFs) and topics provided by the user. It utilizes machine learning models for text embeddings and leverages Google's Gemini and Vertex AI API for document processing and quiz generation. Streamlit is used for the user interface to make it interactive and easy to use.

## Pipeline Overview

1. Document processing using Google Gemini.
2. Text embeddings with Langchain.
3. Integration of Google Service Account for authentication.
4. PDF loader to ingest documents.
6. Generating quizzes based on user input topics.
7. Providing explanations for quiz answers.


## Usage

To run the Quiz Builder:

1. Install the necessary dependencies listed in `requirements.txt`.
2. Run the Streamlit application by executing `streamlit run xxx.py` in the terminal where xxx is the name of the py file you want to run.
3. Follow the instructions provided in the user interface to interact with the Quiz Builder.
