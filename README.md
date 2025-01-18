# FAQ-Assistant

## Overview

FAQ-Assistant is a powerful tool designed to manage and automate frequently asked questions using advanced language models. It leverages Jupyter Notebooks, Python, and Streamlit to provide an interactive and user-friendly interface for creating, managing, and deploying FAQ systems. The system utilizes the Google PaLM (Pathways Language Model) for natural language understanding and generation, along with LangChain for building and deploying language model applications.

## Features

- **Interactive Notebooks**: Create and manage FAQs using Jupyter Notebooks.
- **Python Integration**: Utilize Python scripts for data processing and analytics.
- **Streamlit Web Interface**: Deploy a simple and intuitive web interface for end-users.
- **Advanced Language Model**: Powered by Google PaLM for accurate and efficient language processing.
- **LangChain Integration**: Build and deploy language model applications using LangChain.
- **Environment Management**: Manage environment variables with `python-dotenv`.
- **Efficient Data Handling**: Use `faiss-cpu` for efficient similarity search and clustering.
- **Tokenization**: Handle tokenization tasks efficiently with `tiktoken`.

## Installation

To install and run FAQ-Assistant, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/mykghritlahre/FAQ-Assistant.git
   ```
2. Navigate to the project directory:
   ```bash
   cd FAQ-Assistant
   ```
3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

### Using Jupyter Notebook

1. Open Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
2. Navigate to the `notebooks` directory.
3. Open the desired notebook and start managing your FAQs.

### Using Streamlit Interface

1. Run the Streamlit application:
   ```bash
   streamlit run main.py
   ```
2. Open your web browser and navigate to the provided local URL.

## Project Structure

```
FAQ-Assistant/
├── .ipynb/          # Directory for Jupyter Notebooks
├── main.py             # Streamlit application entry point
├── requirements.txt    # Project dependencies
├── .env                # Environment variables file
├── README.md           # Project README
```

## LangChain

LangChain is used in FAQ-Assistant to build and deploy language model applications. For more information, refer to the [LangChain documentation](https://pypi.org/project/langchain/).

## Google PaLM

FAQ-Assistant uses Google PaLM for natural language processing tasks. For more information, refer to the [Google PaLM documentation](https://ai.google.dev/api/palm).

## Contributing

We welcome contributions! Please read the `CONTRIBUTING.md` for details on the code of conduct, and the process for submitting pull requests.

## Acknowledgements

- Special thanks to Google for providing the PaLM model.
- Special thanks to the LangChain team for their comprehensive tools and documentation.


