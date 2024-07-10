# QueryPDFs

## Purpose: To Solve Problem in finding proper answer from PDF content.

PDF having many pages if user want to find any question's answer then they need to spend time to understand and find the answer. 

The purpose of this project is to create a chatbot that can interact with users and provide answers from a collection of PDF documents. The chatbot uses natural language processing and machine learning techniques to understand user queries and retrieve relevant information from the PDFs. By incorporating OpenAI models, the chatbot leverages powerful language models and embeddings to enhance its conversational abilities and improve the accuracy of responses.

## Features

- Multiple PDF Support: The chatbot supports uploading multiple PDF documents, allowing users to query information from a diverse range of sources.
- Conversational Retrieval: The chatbot uses conversational retrieval techniques to provide relevant and context-aware responses to user queries.
- Language Models: The project incorporates OpenAI models for natural language understanding and generation, enabling the chatbot to engage in meaningful conversations.
- PDF Text Extraction: The PDF documents are processed to extract the text content, which is used for indexing and retrieval.
- Text Chunking: The extracted text is split into smaller chunks to improve the efficiency of retrieval and provide more precise answers.

## Usage

-  Upload PDF documents: Use the sidebar in the application to upload one or more PDF files.
-  Ask questions: In the main chat interface, enter your questions related to the content of the uploaded PDFs.
-  Receive answers: The chatbot will generate responses based on the information extracted from the PDFs.

## Sample Output

![QueryPDF](https://github.com/Abdullahw72/langchain-chatbot-multiple-PDF/blob/master/QueryPDF.png?raw=true)

![ChatBot WorkFlow](https://github.com/Abdullahw72/langchain-chatbot-multiple-PDF/blob/master/ChatBot WorkFlow.webp?raw=true)

![QueryPDF Flow](https://github.com/Abdullahw72/langchain-chatbot-multiple-PDF/blob/master/QueryPDF Flow.webp?raw=true)


## Installation

To install and run the Langchain Chatbot, follow these steps:

Clone the repository 

```
git clone <repo-url>
```

Add your OpenAI Key by creating a .env file in the folder and add the following within it:

```
OPENAI_API_KEY=
OPENAI_MODEL_NAME=gpt-3.5-turbo
```

Create a Virtual Environment

```
pip install virtualenv
```

to run this app do activate environment and run app

```
python3 -m venv query-pdf-environment
```

```
source query-pdf-environment/bin/activate
```

Install the dependencies using requirements.txt

```bash
pip install -r requirements.txt
```

```
streamlit run app.py
```

## Refrence Blog
Check out my detailed blog on this project here: 

