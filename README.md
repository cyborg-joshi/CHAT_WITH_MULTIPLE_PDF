# CHAT_WITH_MULTIPLE_PDF
The MultiPDF Chat App lets you ask questions about multiple PDFs using natural language. It provides relevant answers based on document content, powered by a language model. Note: It responds only to queries related to uploaded PDFs.
![image](https://github.com/cyborg-joshi/CHAT_WITH_MULTIPLE_PDF/assets/91533278/2cc21249-ff3c-4595-bd08-7118405d3578# MultiPDF Chat App


## Functionality Overview

The application follows these steps to provide responses to user questions:

1. **PDF Loading**: The app reads multiple PDF documents and extracts their text content.
   
2. **Text Chunking**: The extracted text is divided into smaller chunks for effective processing.

3. **Language Model**: Utilizes a language model to generate vector representations (embeddings) of the text chunks.

4. **Similarity Matching**: Compares user questions with text chunks to identify the most semantically similar ones.

5. **Response Generation**: Selected chunks are passed to the language model, which generates responses based on the relevant content of the PDFs.

## Dependencies and Installation

To install the MultiPDF Chat App, please follow these steps:

1. Clone the repository to your local machine.
   
2. Install the required dependencies by running:
