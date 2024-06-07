# E-Commerce-Chatbot

# E-Commerce Chatbot

This repository contains an implementation of an e-commerce chatbot designed to assist users with their shopping needs, answer questions, and provide recommendations. The chatbot uses Retrieval-Augmented Generation (RAG) and web scraping from Flipkart to collect the dataset.

How to run?

```
conda create -p venv python==3.10 -y
```

```
conda activate venv
```

```
pip install -r requirements.txt
```

## Features

- **Natural Language Processing (NLP)**: Understands and processes user queries.
- **Product Recommendations**: Provides product suggestions based on user input.
- **Web Scraping**: Collects data from Flipkart for product reviews and details.
- **User-Friendly Interface**: Web-based interface for easy interaction.

## Tech Stack

- **LangChain**: Used for managing the conversational AI components.
- **Python**: Core programming language for the project.
- **OpenAI**: Utilized for natural language understanding and response generation.
- **Flask**: Web framework for developing the chatbot interface.
- **Astra DB**: Database for storing and retrieving chatbot data.
- **Datasets**: Used for handling and processing data.
- **pypdf**: Library for PDF processing.
- **python-dotenv**: For managing environment variables.

## Directory Structure

- `data_converter.py`: Script for converting and preprocessing data.
- `ingest.py`: Script for ingesting data into the database.
- `retrieval_generation.py`: Core logic for retrieval and generation using the RAG approach.
- `flipkart_product_review.csv`: Dataset containing product reviews scraped from Flipkart.
- `requirements.txt`: Lists all dependencies.
- `app.py`: Main application script.

## Usage

After starting the application, navigate to `http://localhost:5000` in your web browser to interact with the chatbot.
