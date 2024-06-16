# FlavourSaurus, a dino-mic cooking AI bot 🦖
![Designer (1)](https://github.com/omkarb09/Flavorsaurus/assets/44408619/5782f4e1-64fd-4138-b225-f568940391cd)

## Introduction
FlavorSaurus is a cutting-edge AI-powered cooking assistant that suggests food recipes based on your ingredients, allergies, and food preferences. Built using Nvidia NIM endpoints and LangChain, FlavorSaurus is integrated with Pinecone for its vector database and utilizes Gradio for an interactive user interface.

## Features
- Ingredient-Based Recipe Suggestions: Enter the ingredients you have, and FlavorSaurus will suggest recipes you can make with them
- Allergy Consideration: Specify your allergies, and FlavorSaurus will ensure all suggested recipes are safe for you
- Food Preferences: Indicate your dietary preferences (e.g., vegan, gluten-free) to receive personalized recipe recommendations
- Interactive UI: Use a simple and intuitive interface powered by Gradio to interact with FlavorSaurus

## Technology Stack
- Nvidia NIM Endpoints: For natural language processing and understanding, FlavorSaurus uses 'meta/llama3-8b-instruct' from Nvidia NIM endpoints
- LangChain: Facilitates seamless interaction with the language model
- Embedding model:  FlavorSaurus uses 'all-MiniLM-L6-v2' from 'sentence_transformers' library for embedding
- Pinecone: A vector database that enables efficient and scalable storage and retrieval of recipe data
- Gradio: Provides a user-friendly interface for interacting with FlavorSaurus

## Prerequisites
- Python 3.8+
- Nvidia NIM API access
- Pinecone API access
- Gradio

## Usage
1. Install Required Libraries:
- Open code.ipynb in Jupyter Notebook or Jupyter Lab
- Run all cells under the markdown Installing required libraries to install all required libraries
2. Import Libraries:
- Run the cell under the markdown Import statements to import all necessary libraries
3. Set API Keys and Environment Variables:
- Run the cell under the markdown Setting the API keys and environment variables to set up API keys and constants from config.json
4. Define Pinecone Query Functions:
- Run the cell under the markdown Query functions for the AI agent to define the code for Pinecone query functions
5. Define the AI Agent:
- Run the cell under the markdown Code for the AI agent to set up the LangChain runnable and function used to query the LLM
6. Set Up the Gradio UI:
- Run the cell under the markdown Code for the Gradio UI to define the Gradio user interface
7. Launch the UI:
- Run the next cell to launch the Gradio interface. Note the localhost URL provided in the output
8. Access the Interface:
- Open your web browser and navigate to the provided localhost URL to interact with FlavorSaurus
9. Close the Gradio App:
- When you're finished, run the subsequent cell to shut down the Gradio application

## Contact
For any questions or feedback, please open an issue on the GitHub repository or contact me at omkar.bhatkande@gmail.com
