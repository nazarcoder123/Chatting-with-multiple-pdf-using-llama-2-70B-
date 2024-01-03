# Chatting-with-multiple-pdf-using-llama-2-70B-Chat
This repository contains the code for a Multi-Docs ChatBot built using Streamlit, Hugging Face models, and the llama-2-70b language model. The chatbot processes uploaded documents (PDFs, DOCX, TXT), extracts text, and allows users to interact with a conversational chain powered by the llama-2-70b model. 

# How It Works
The application follows these steps to provide responses to your questions:

1.PDF Loading: The app reads multiple PDF documents and extracts their text content.

2.Text Chunking: The extracted text is divided into smaller chunks that can be processed effectively.

3.Language Model: The application utilizes a language model to generate vector representations (embeddings) of the text chunks.

4.Similarity Matching: When you ask a question, the app compares it with the text chunks and identifies the most semantically similar ones.

5.Response Generation: The selected chunks are passed to the language model, which generates a response based on the relevant content of the PDFs.

# Dependencies and Installation
To install the MultiPDF OR Docs Chat App, please follow these steps:

Clone the repository to your local machine.

Install the required dependencies by running the following command:

pip install -r requirements.txt

Obtain an API key from Replicate and add it to the .env file in the project directory.

REPLICATE_API_TOKEN = I have provided the api key already

# Usage
To use the MultiPDF OR DOCS Chat App, follow these steps:

1.Ensure that you have installed the required dependencies and added the Replicate API key to the .env file.

2.Run the app.py file using the Streamlit CLI. Execute the following command:

streamlit run app.py

3.The application will launch in your default web browser, displaying the user interface.

4.Load multiple PDF documents into the app by following the provided instructions.

5.Ask questions in natural language about the loaded PDFs using the chat interface.
