# FlavorSaurus, a dino-mic cooking AI bot 🦖🍲
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
1. Have Python 3.8+ installed.
2. Make sure to have the config.json file in the same directory as the code.ipynb. Also make sure config.json has the working API keys for Nvidia NIM and Pinecone, index name for Pinecone, LLM model name and embedding model name
3. In code.ipynb, Run all cells under the markdown 'Installing required libraries' to install all required libraries
4. Run the cell under the markdown 'Import statements' to import all required libraries
5. Next run the cell under the markdown 'Setting the API keys and environment variables' to set the API keys and constants
6. Run the cell under the markdown 'Query functions for the AI agent' to define the code for the pinecone query functions
7. Next run the cell under the markdown 'Code for the AI agent' to define the Langchain runnable and function used to query the LLM
8. Run the cell under the markdown 'Code for the Gradio UI' to define the code for the gradio ui
9. Run the next cell to launch the ui. Use the give localhost url on your browser to open the interface.
10. Run the next cell to close the gradio app.

## Contact
For any questions or feedback, please open an issue on the GitHub repository or contact me at omkar.bhatkande@gmail.com

### Happy Cooking with FlavorSaurus! 🦖🍲
