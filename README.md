# Food Recommendation RAG System

This repository contains a comprehensive project focused on building an intelligent food recommendation engine using vector databases and Retrieval-Augmented Generation (RAG). 

## 🎯 Project Overview

This project demonstrates practical applications of vector databases in search platforms and conversational AI systems. It explores three distinct approaches to handling search queries: simple similarity search, advanced metadata filtering, and full conversational AI interfaces.

## ✨ Key Features

* **Interactive CLI Search:** A real-time food search interface that responds immediately to user queries via an interactive terminal loop.
* **Advanced Search Filtering:** Sophisticated filtering capabilities combining vector similarity search with strict metadata constraints.
* **RAG (Retrieval-Augmented Generation) Chatbot:** An intelligent bot that combines vector similarity search with contextual response generation for a natural language experience.
* **System Architecture Comparison:** Built-in tools to benchmark and compare when to use simple similarity search versus advanced conversational interfaces.

## 🗂️ Project Structure

* `enhanced_rag_chatbot.py`: The main conversational AI system and context tracker.
* `interactive_search.py`: Command-line application for basic interactive similarity searches.
* `advanced_search.py`: Implementation of search alongside complex metadata filters.
* `system_comparison.py`: Utilities for comparing the different search approaches.
* `shared_functions.py`: Reusable modular components, error handling, and shared code.
* `FoodDataSet.json`: The core dataset containing the food items and their metadata.

## 🛠️ Technology Stack & Skills

* **Python:** Core application logic and modular architecture.
* **Chroma DB:** Creating collections, populating data, and applying metadata filters.
* **Vector Similarity:** Utilizing cosine similarity to identify closely matching documents.
* **Conversational AI Techniques:** Intent recognition and basic context tracking.

## 🚀 Getting Started

1. Clone the repository:
   ```bash
   git clone [https://github.com/AkhileshRaoGandra/food_recommendation_RAG.git](https://github.com/AkhileshRaoGandra/food_recommendation_RAG.git)
