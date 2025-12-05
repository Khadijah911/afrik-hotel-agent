Afrik Hotel Agent

Afrik Hotel Agent is an AI-powered assistant that helps users find information about hotels in African countries. It uses a combination of RAG (Retrieval-Augmented Generation), OpenAI,langgraph and Gradio to answer questions about hotel contact details, facilities, ratings, and recommendations.

Features
Search hotels by name, city, or country
Get contact details (phone, address, website, fax)
Recommend hotels based on user needs
Compare hotels
Provide facilities and descriptions
Fallback online search when phone information is missing
Chat interface built with Gradio

How It Works
Thee kaggle hotel dataset is converted into text documents.
The documents are embedded and stored using FAISS.
A RAG chain retrieves relevant hotel data.
The LLM generates responses using a custom prompt.
If needed, a web search tool fetches missing phone numbers or details.
The user interacts with the system through a Gradio chat interface.


Set your API keys:
OPENAI_API_KEY=your_key
SERPER_API_KEY=your_key



Files
afrik_hotels_gpt.py – Main application code
Afrik_hotels_gpt.ipynb – Notebook version
README.md – Project documentation
