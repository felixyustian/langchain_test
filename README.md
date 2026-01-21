# LangChain Capabilities Test


This repository serves as a testing ground for exploring the capabilities of the **LangChain** framework. It includes experimental code (likely in Jupyter Notebook format) to demonstrate how to build and orchestrate LLM-powered applications using Chains, Agents, and Prompt Templates.

## 📄 Repository Contents

* `LangChain_Test.ipynb` (or similar): The main notebook containing the experimental code.
* `README.md`: Project documentation.

## 🚀 Overview

The goal of this project is to validate and understand various LangChain components, including:
* **Prompt Management**: Creating and optimizing templates for LLMs.
* **Chains**: Linking multiple LLM calls or tools in a sequence.
* **Memory**: managing conversation history.
* **Agents**: Implementing reasoning loops where the LLM decides which tools to use.

## 🛠️ Technology Stack

* **Language**: Python 3.x
* **Framework**: [LangChain](https://github.com/langchain-ai/langchain)
* **LLM Provider**: (e.g., OpenAI, Google Gemini, or Hugging Face)
* **Environment**: Jupyter Notebook / Google Colab

## 📋 Prerequisites

To run the experiments, you need:

1.  **Python 3.9+**
2.  **API Keys**: Ensure you have valid keys for your LLM provider (e.g., `OPENAI_API_KEY` or `GOOGLE_API_KEY`).

## 🔧 Installation & Usage

1.  **Clone the Repository**
    ```bash
    git clone [https://github.com/felixyustian/langchain_test.git](https://github.com/felixyustian/langchain_test.git)
    cd langchain_test
    ```

2.  **Install Dependencies**
    ```bash
    pip install langchain langchain-openai langchain-community jupyter
    ```

3.  **Run the Notebook**
    ```bash
    jupyter notebook
    ```
    Open the `.ipynb` file to run the cells and observe the LangChain outputs.

## 📄 License

This project is distributed under the **GPL-3.0 License**. See the `LICENSE` file for more details.
