# Chat-Pandas DataFrame Interaction

This repository provides a chat-like interface for interacting with pandas DataFrames, making data analysis accessible to non-technical users. By integrating LangChain's create_pandas_dataframe_agent, users can ask data-related questions, request insights, and navigate through their data conversationally, as if chatting with a friend. This agent leverages the power of Meta's LLaMA 2 LLM model to generate responses based on user queries.

## Features
* Conversational Data Interaction: Users can interact with their data using natural language queries.
* Data Analysis Made Easy: Non-technical users can perform complex data analyses without writing any code.
* Automated Insight Generation: The agent generates Python code based on user prompts, executes it, and summarizes the data.
* Conversational Format Responses: The LLM model converts data into a conversational format for easy understanding.

## Installation
1. Clone or download the repository
2. Download Ollama and pull the Llama2 model (command: ollama pull llama2)
4. Create and activate a virtual environment
3. Install project dependencies using command: pip install -r requirements.txt
4. Run the app using command: streamlit run app.py
