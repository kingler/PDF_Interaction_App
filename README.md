
# PDF Interaction Web Application

This project is a web application for interacting with PDF files using OpenAI's embedding endpoint. The application allows users to upload PDF files, select PDFs to talk to, and enter a query. The application then uses OpenAI's embedding endpoint to embed the query and search the selected PDFs for relevant information.

## Project File Structure

- `modify.py`: This file contains the `OpenAIEmbeddings` class that has methods to embed texts.
- `pdf.py`: This file contains a function `main` that loads vector databases, loads combined indexes, and runs an interactive loop to select indexes and query.
- `pdf_st.py`: This file defines a Streamlit application that allows users to upload PDF files, select PDFs to talk to, and enter a query.
- `requirements.txt`: This file contains the list of Python packages required for the project.
