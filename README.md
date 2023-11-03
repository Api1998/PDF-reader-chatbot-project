# PDF Chatbot using NLP

An NLP project that allows you to upload PDF files and use large language models to create a chatbot-like interface to answer questions related to the content in the PDFs. The web application is built using Streamlit.



## Table of Contents

- [About](#about)
- [Demo](#demo)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)


## About

The PDF Chatbot using NLP project is designed using langchain to take PDF files as input, process their content using large language models, and provide a chatbot-like interface where users can ask questions related to the PDF content and receive answers. This uses OpenAI LLM to interact with the contents in the PDFs.

## Demo



## Getting Started

Follow these steps to set up the project on your local machine.

### Prerequisites

Before you begin, make sure to install the dependencies from requirements file by running the following command

```bash
pip install -r requirements.txt
```

### Installation

1. Clone the repository:

```bash
git clone https://github.com/Api1998/PDF-reader-chatbot-project.git
```
## Usage

1) create an OpenAI account and obtain a API token key
2) Place the key in the .env file to the respective variable
3) Run the streamlit app using following command
```bash
streamlit run app.py
```
4) Upload the PDF files that you want to process and click process
5) Ask any questions related to the content in the PDFs
6) Enjoy the chat with the PDF reader chatbot to get to know things about PDFs

### *** Important

Using OpenAI API token is subjected to pricing. You can also use from LLM models from HuggingFace or other platforms as well
