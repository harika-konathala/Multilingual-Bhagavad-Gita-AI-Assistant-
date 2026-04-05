# Multilingual-Bhagavad-Gita-AI-Assistant-
Bhagavad Gita AI Assistant with semantic verse search, multilingual translation, and voice responses using Python, FAISS, and Streamlit.
# Bhagavad Gita AI Assistant

An AI-powered chatbot that retrieves relevant Bhagavad Gita verses using semantic search and natural language queries.  
The system allows users to ask questions in simple language and receive the most relevant sloka along with translation and optional audio narration.

This project demonstrates practical applications of NLP, vector search, and interactive AI interfaces.

---

## Project Overview

The Bhagavad Gita contains deep philosophical teachings across multiple chapters and verses. Searching for relevant verses using traditional keyword matching can be difficult because users may phrase questions differently.

This project solves that problem using **semantic search**. Instead of keyword matching, the system converts both user queries and verse meanings into vector embeddings and retrieves the most semantically similar verses.

Users can:
- Ask questions in natural language
- Retrieve the most relevant sloka
- View chapter and verse details
- Translate meaning into multiple languages
- Listen to the verse through text-to-speech

---

## Features

- Semantic search over Bhagavad Gita verses
- Natural language question answering
- Vector similarity search for accurate retrieval
- Multilingual translation support
- Voice narration using text-to-speech
- Interactive web interface

---

## Tech Stack

Python – Core programming language  
Pandas – Data preprocessing and dataset handling  
Sentence Transformers – Text embedding generation  
FAISS – Vector similarity search engine  
Streamlit – Interactive web application interface  

---

## System Architecture

User Query  
↓  
Text Embedding using Sentence Transformers  
↓  
Vector Similarity Search using FAISS  
↓  
Retrieve Top Matching Verse  
↓  
Display Sloka, Meaning, and Audio Output

---

## Dataset

The dataset contains Bhagavad Gita verses with the following fields:

- Chapter
- Verse
- Shloka
- Transliteration
- Hindi Meaning
- English Meaning
- Word Meaning

The semantic search model uses **English meaning of verses** to generate embeddings and retrieve relevant results.

---

## Example Use Cases

User queries supported by the system:

- What does the Gita say about anger?
- How can a person find peace?
- What is the meaning of karma?
- How should a person control desires?

The system retrieves the most relevant verses that address these philosophical concepts.

---

## Project Structure
gita-ai-assistant
│
├── app.py
├── Bhagwad_Gita.csv
├── requirements.txt
└── README.md
