# PDF Chat Application using Gemini 💬

## Overview

This Python application utilizes the [Gemini](https://google.generativeai.dev/gemini) model to enable users to interact with the text content of PDF files through a conversational interface. The application processes PDF files, extracts text data, splits it into chunks, and creates a vector store for efficient querying.

## Requirements

Ensure you have the required dependencies installed by running:

```bash
pip install -r requirements.txt
```

## Usage

1. **Environment Setup:**
   - Set up a virtual environment and install the necessary dependencies.

2. **Configuration:**
   - Create a `.env` file and add the required environment variables:
     - `GOOGLE_API_KEY`: Your Google API key for Gemini model access.

3. **Run the Application:**
   - Execute the main script `main.py`:

     ```bash
     python main.py
     ```

4. **Use the Streamlit UI:**
   - Open a web browser and navigate to the provided Streamlit UI.
   - Upload PDF files containing the content you want to interact with.
   - Enter a question in the input box and click "Submit & Process" to get a response based on the PDF content.

## Code Structure

- `main.py`: The main script containing the Streamlit UI and the core functionalities.
- `langchain`: A module for various language processing functionalities.
- `models`: Model files used for embeddings and similarity search.
- `requirements.txt`: List of Python dependencies.

## Important Notes

- Make sure to handle your Google API key securely and avoid sharing it publicly.
- The application uses the Gemini model for generative AI responses. Ensure compliance with Google's terms of service.

## Author

This application was developed by [Atomic-man](https://github.com/Atomic-man007/). Feel free to contact for any inquiries or improvements.

---

**Disclaimer:** This application is for educational and experimental purposes. Usage may be subject to the terms and conditions of the underlying models and services, especially when using proprietary APIs like Google's Gemini.

## Streamlit UI

![Alt text](./img/gemini.png?raw=true "Streamlit UI")
