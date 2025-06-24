# AI Chatbot with Memory (OpenAI + Pinecone + LangChain)

This project builds an **AI-powered chatbot** that maintains memory using **Pinecone** and **OpenAI's GPT-4**.

## Features
- ✅ **Understands natural conversations with GPT-4**
-  **Remembers previous messages using Pinecone**
-  **Works in Google Colab or locally**
-  **Retrieves past chats for better context-aware responses**

##  Installation
```sh
pip install openai langchain pinecone-client dotenv

 API Keys Required
You'll need:

OpenAI API Key (For generating responses)
Pinecone API Key (For memory storage)
Set these in your environment:
export OPENAI_API_KEY="your-openai-key"
export PINECONE_API_KEY="your-pinecone-key"

How to Use
1️⃣ Open the ai_chatbot.ipynb notebook in Google Colab or Jupyter.
2️⃣ Run all cells to initialize OpenAI & Pinecone.
3️⃣ Start chatting! The AI will remember past interactions.

 Example
User Input:
Hey AI, what’s the capital of France?

AI Response:
The capital of France is Paris.
User (Later):
And what’s its population?
AI (Remembers Previous Chat):
Paris has a population of approximately 2.1 million.


