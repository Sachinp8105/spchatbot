#  spChatbot

## Project Overview
This project implements a Retrieval-Augmented Generation (RAG) model chatbot using Java (Spring Boot) for the backend, and HTML/CSS/JS for the frontend. The chatbot can process documents, generate embeddings, and respond to user queries.

## Features
- Upload documents or text to generate embeddings.
- Chat interface to interact with the RAG model.
- Uses vector database for efficient retrieval.

## Getting Started

### Prerequisites
- Java 11 or higher
- Maven
- Node.js (for frontend development)
- Vector Database (e.g., Zilliz or Supabase)

### Setup Instructions
1. Clone the repository:
    ```sh
    git clone https://github.com/yourusername/rag-chatbot.git
    cd rag-chatbot
    ```

2. Backend Setup:
    - Configure application properties with your vector database details.
    - Build and run the Spring Boot application:
        ```sh
        mvn clean install
       
