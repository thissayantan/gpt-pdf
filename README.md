# Chat with Multiple PDFs :books:

Chat with Multiple PDFs is a Python web application that enables you to interact with the content of multiple PDF files via natural language chat, using OpenAI's models.

## Description

This application takes in multiple PDF files, extracts the text, and generates chunks of the text. These chunks are embedded into vectors and stored. Using these vectors and a Long-Short-Term-Memory model (LLM), the application creates a conversation chain that allows the user to ask questions and receive answers based on the content of the uploaded PDFs. 

## Installation

This project requires Python 3.6 or later. Clone the repository and install dependencies with:

```bash
git clone git@github.com:thissayantan/gpt-pdf.git
cd gpt-pdf
pip install -r requirements.txt
```

## Usage

To run the application:

```bash
streamlit run main.py
```

The web application provides an interface where you can upload PDF files and ask questions about the content of these documents. 

## Libraries Used 

- **Streamlit**: for the web interface
- **dotenv**: to load environment variables
- **PyPDF2**: to read PDF files
- **langchain**: a custom package to handle text splitting, embeddings, vectorstores, chat models, memory, conversation chains, etc.
- **htmlTemplates**: a custom package for HTML templates

## Contributions

Feel free to submit a pull request to contribute to this project.

## License

This project is licensed under MIT License. For more information, please see the [LICENSE](https://github.com/thissayantan/gpt-pdf/blob/main/LICENSE) file.

## Contact

If you have any questions or suggestions, feel free to open an issue or pull request. 