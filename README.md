# Chat with Multiple PDFs using Gemini

## Deployed on Streamlit: https://chatpdffff.streamlit.app/

This Streamlit application allows you to chat with and get answers from multiple PDF documents using Google's Gemini Pro model and LangChain framework. It's a powerful way to quickly extract information and insights from your PDFs.

## Features

* **Multiple PDF Uploads:**  Easily upload and process multiple PDFs at once.
* **Gemini Pro Model:** Leverages the advanced capabilities of Google's Gemini Pro for intelligent and accurate question answering.
* **LangChain Integration:** Utilizes LangChain to efficiently manage document loading, text splitting, and vector storage.
* **FAISS Vector Store:**  Employs FAISS for fast and effective similarity search to retrieve relevant information.
* **Streamlit UI:**  Provides a user-friendly interface to ask questions and view answers.

## How to Use

1. **Installation:**
   * Clone this repository.
   * Install the required libraries: `pip install streamlit PyPDF2 langchain langchain-google-genai faiss-cpu google-generativeai python-dotenv`
   * Obtain a Google API key and set it as an environment variable named `GOOGLE_API_KEY`.

2. **Run the App:**
   * Start the Streamlit app from your terminal: `streamlit run app.py`
   * Your web browser will open to the app's interface.

3. **Upload PDFs:**
   * In the sidebar, click "Browse files" and select your PDF documents.
   * Click "Submit & Process" to extract text and create the vector database.

4. **Ask Questions:**
   * Type your question in the text box and press Enter.
   * The app will analyze your PDFs and provide the most relevant answer.

## Key Modules and Libraries

* **Streamlit:** The web framework for creating the user interface.
* **PyPDF2:** Used to read and extract text from PDF documents.
* **LangChain:** Simplifies the workflow for working with language models and data.
* **Langchain-Google-Genai:** Provides integration with Google's generative AI models and embeddings.
* **FAISS:** A library for efficient similarity search and clustering of dense vectors.
* **Google Generative AI:** Google's API for accessing Gemini and other powerful models.
* **Python-dotenv:**  Loads environment variables from a `.env` file.

## Contributing

Contributions are welcome! Feel free to open issues or submit pull requests. 

