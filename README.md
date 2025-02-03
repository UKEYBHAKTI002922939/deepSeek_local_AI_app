# AI Programming Buddy
# Using Deepseek locally on Mac

This repository showcases an AI-powered pair programming assistant built with Streamlit for a user-friendly interface. It leverages the capabilities of **deepseek r1 7b** (a powerful large language model) and **LangChain** to provide intelligent code suggestions, explain code, and even help debug your code.

**Key Features:**

* **Code Generation:** Generate code snippets, functions, or even entire classes based on your natural language prompts.
* **Code Explanation:** Get clear and concise explanations of any code snippet, helping you understand its functionality.
* **Code Debugging:** Describe the errors you're encountering, and the assistant will provide potential solutions and debugging steps.
* **Code Refactoring:** Refactor existing code for better readability, performance, or maintainability.
* **User-Friendly Interface:** Streamlit provides an intuitive and interactive interface for easy interaction with the AI assistant.

**Technologies Used:**

* **deepseek r1 7b:** A powerful and versatile large language model.
* **LangChain:** A framework for developing and deploying applications powered by language models.
* **Streamlit:** A Python library for building beautiful and interactive web applications.
* **Ollama:** Get up and running with large language models.

### Ensure you download the model locally before running the code
**Getting Started:**

1. **Create a virtual environment (recommended):**
   ```bash
   python3 -m venv .venv 
   source .venv/bin/activate 

2. **Install dependencies:**
   ```bash
   pip install -r requirements.txt



3. **Run App:**
   ```bash
   streamlit run app.py

