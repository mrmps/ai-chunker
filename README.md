# Streamlit Text Chunker

This Streamlit application uses AI to chunk input text into coherent sections. It leverages OpenAI's GPT model to determine appropriate chunk boundaries and provide context for each chunk.

## Features

- User-friendly web interface for text input
- AI-powered text chunking
- Visualization of chunks with context

## Prerequisites

- Python 3.7+
- OpenAI API key

## Installation

1. Clone this repository:
   ```
   git clone https://github.com/yourusername/streamlit-text-chunker.git
   cd streamlit-text-chunker
   ```

2. Install the required packages:
   ```
   pip install -r requirements.txt
   ```

3. Set up your environment variables:
   Create a `.env` file in the project root and add your OpenAI API key:
   ```
   OPENAI_API_KEY=your_api_key_here
   ```

## Usage

Run the Streamlit app:
```
streamlit run text_chunker_app.py
```

Open your web browser and navigate to `http://localhost:8501`.

## Deployment

This app can be deployed using various methods, including:
- Streamlit Cloud
- Heroku
- Google Cloud Platform
- Amazon Web Services
- DigitalOcean

Refer to the deployment section in the code comments for more details.

## Rate Limiting

This application implements rate limiting to prevent abuse and manage API usage. By default, it allows 5 requests per minute per user.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License.# ai-chunker
