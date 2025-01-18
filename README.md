# FAQ-Assistant

## Overview

FAQ-Assistant is a tool designed to assist in managing and automating frequently asked questions. It leverages Jupyter Notebooks and Python to provide an interactive environment for creating, managing, and deploying FAQ systems. Additionally, it uses Streamlit to offer a simple and intuitive web interface for end-users.

## Features

- **Interactive Notebooks**: Utilize Jupyter Notebooks for creating and managing FAQs.
- **Python Integration**: Leverage Python scripts to process and analyze FAQ data.
- **Streamlit Web Interface**: Simple and intuitive web interface for ease of use.
- **Environment Management**: Uses `python-dotenv` for environment variable management.
- **Efficient Data Handling**: Utilizes `faiss-cpu` for efficient similarity search and clustering.
- **Tokenization**: Uses `tiktoken` to handle tokenization tasks efficiently.

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

To start using FAQ-Assistant:

1. Open Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
2. Navigate to the directory containing the FAQs.
3. Open the desired notebook and start managing your FAQs.

Alternatively, to use the Streamlit interface:

1. Run the Streamlit application:
   ```bash
   streamlit run app.py
   ```
2. Open your web browser and navigate to the provided local URL.

## Project Structure

```
FAQ-Assistant/
├── notebooks/          # Directory for Jupyter Notebooks
├── main.py              # Streamlit application entry point
├── requirements.txt    # Project dependencies
├── .env                # Environment variables file
└── README.md           # Project README
```

