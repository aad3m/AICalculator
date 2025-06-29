# AI Calculator

A simple command-line AI assistant built with Python and LangChain. The assistant can perform arithmetic calculations and chat with users using OpenAI's language model.

## Features

- Chat with an AI assistant
- Perform arithmetic calculations (addition)
- Extensible with more tools

## Requirements

- Python 3.8+
- OpenAI API key
- Dependencies

## Setup

1. Clone the repository.
2. Install dependencies
3. using pip:
   ```bash
   uv add streamlit openai PyPDF2 python-dotenv
   ```

3. Set up your OpenAI API key:
   - Create a `.env` file in the root directory.
   - Add your OpenAI API key in the format: `OPENAI_API_KEY=your_api_key_here`
   - Alternatively, set the environment variable `OPENAI_API_KEY` in your system.
4. Run the assistant:
   ```bash
   uv run streamlit run main.py
   ```

Type your questions or calculation requests. Type `quit` to exit.

## Extending

Add more tools by defining functions with the `@tool` decorator.