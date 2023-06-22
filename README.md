# LLM Powered Document Chat

LLM Powered Document Chat is a web-based application powered by Streamlit and large language models (LLMs). It enables users to engage in a chat-based interaction with document repositories, allowing for information retrieval in a conversational manner.

## Description

This application takes in multiple PDF files, extracts the text, and generates chunks of the text. These chunks are embedded into vectors and stored. Using these vectors and a Long-Short-Term-Memory model (LLM), the application creates a conversation chain that allows the user to ask questions and receive answers based on the content of the uploaded PDFs. 

## Installation

Clone the repository:

```bash
git clone git@github.com:thissayantan/gpt-pdf.git
cd gpt-pdf
```

The project uses [Poetry](https://python-poetry.org/) for dependency management. If you don't have it installed, you can install it as follows:

For macOS / Linux / BashOnWindows:

```bash
curl -sSL https://install.python-poetry.org | python -
```

For Windows PowerShell:

```powershell
(Invoke-WebRequest -Uri https://install.python-poetry.org -UseBasicParsing).Content | python -
```

Install the necessary dependencies:

```bash
poetry install
```

Set up the environment variables (including OpenAI API key, if applicable) in a `.env` file.

## Usage

Start the Streamlit application:

```bash
streamlit run app.py
```

In the interface, select the LLM and embeddings model, upload documents, and start the conversation.

## Example

```python
# Start the application
streamlit run app.py

# In the application:
# 1. Choose an LLM from the dropdown (e.g., "OpenAI").
# 2. Choose an embeddings model (e.g., "OpenAI").
# 3. Upload a PDF or text document.
# 4. Click "Process" to process the documents and prepare the chat.
# 5. Type your question into the chat box and press enter to receive a response.
```

## Contributions

Feel free to submit a pull request to contribute to this project.

## License

This project is licensed under MIT License. For more information, please see the [LICENSE](https://github.com/thissayantan/gpt-pdf/blob/main/LICENSE) file.

## Contact

If you have any questions or suggestions, feel free to open an issue or pull request. 