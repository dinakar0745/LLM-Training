# LLM Training

## Overview

This repository contains a Python script that utilizes the LangChain library to perform document loading, text splitting, vector database creation, and question answering with a Retrieval-Augmented Generation (RAG) approach. The script is designed to work with both local and online PDF files and uses a combination of various LangChain components to achieve this functionality.

## Requirements
- Python 3.8 or higher
- LangChain library and its dependencies
- Installation

To install the required dependencies, use command:
    ```bash
    pip install langchain langchain_community langchain_core
    ```

## Usage
### Local PDF File Processing
- Ensure you have a local PDF file available. Update the local_path variable with the path to your PDF file.
- Run the script to load the PDF, split the text into chunks, and add it to a vector database.
- The script uses a pre-trained language model to generate multiple versions of a user query to retrieve relevant documents from the vector database.
- Finally, it uses a RAG approach to answer the question based on the retrieved documents.

## Contributing
Contributions are welcome! Please feel free to submit a pull request or open an issue to discuss improvements or suggestions.

## License
This project is licensed under the MIT License. See the LICENSE file for more details.