# LangChain: Summarize Text From YT or Website

This project is a Streamlit application that uses LangChain to summarize text from YouTube videos or websites. The application leverages the Groq API and various document loaders to fetch and summarize content.

## Features

- Summarize content from YouTube videos or websites.
- Uses the Groq API for language model processing.
- Simple and intuitive Streamlit interface.

## Installation

1. Install the required packages:

    ```bash
    pip install -r requirements.txt
    ```

2. Create a `.env` file in the root directory and add your API keys:

    ```properties
    LANGCHAIN_API_KEY = "your_langchain_api_key"
    LANGCHAIN_PROJECT = "Text_Summarization"
    HF_TOKEN = "your_hf_token"
    GROQ_API_KEY = "your_groq_api_key"
    ```

## Usage

1. Run the Streamlit application:

    ```bash
    streamlit run app.py
    ```

2. Open your web browser and go to `http://localhost:8501`.

3. Enter your Groq API key in the sidebar.

4. Enter the URL of the YouTube video or website you want to summarize.

5. Click the "Summarize the Content from YT or Website" button.

## Project Structure

- `app.py`: The main Streamlit application file.
- `requirements.txt`: The list of required Python packages.
- `.env`: Environment variables file (not included in the repository).

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.
