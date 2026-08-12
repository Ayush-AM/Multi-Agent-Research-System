# Multi-Agent Research System

A fully automated, multi-agent AI research pipeline that gathers, analyzes, and drafts complete research reports. It is built using **Python, LangChain, and Streamlit**, and powered by **Groq's Llama 3** engine for incredibly fast reasoning.


## Tech Stack

- **Languages**: Python
- **Frameworks & Libraries**: Streamlit, LangChain, Pandas, Groq API

## Features
- **Multi-Agent Architecture**: Uses distinct agents for searching, deep-reading (scraping), writing, and critiquing.
- **Fast Generation**: Uses Groq API and `llama-3.3-70b-versatile` under the hood.
- **Modern UI**: Clean and stylish web interface provided by Streamlit.

## Setup Instructions

1. Clone the repository
2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Create a `.env` file in the root directory with your API keys:
   ```env
   GROQ_API_KEY=your_groq_api_key_here
   TAVILY_API_KEY=your_tavily_api_key_here
   ```
4. Run the Streamlit application:
   ```bash
   streamlit run app.py
   ```
