# A Simple ReAct Agent 

This project demonstrates how to use the OpenAI API through OpenRouter to generate chat-based responses using a Jupyter Notebook.

## Prerequisites
- Python 3.8 or later
- Jupyter Notebook or JupyterLab
- OpenRouter API key with access to the model `meta-llama/llama-3.2-90b-vision-instruct:free`
- Required Python libraries: `openai`

## Installation
1. Install the necessary library:
   ```bash
   pip install openai notebook
   ```

2. Set your OpenRouter API key:
   ```bash
   export OPENROUTER_API_KEY=<your-api-key>
   ```

## How to Run
1. Open the Jupyter Notebook:
   ```bash
   jupyter notebook openai_chat_example.ipynb
   ```

2. Follow the steps in the notebook cells:
   - Ensure the API key is loaded correctly.
   - Execute the cells to query the model and get the response.

3. View the model's output in the notebook.
