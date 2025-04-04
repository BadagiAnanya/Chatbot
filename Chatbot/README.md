AI Chatbot with RAG using LangChain and Groq
This project builds an AI chatbot leveraging Retrieval-Augmented Generation (RAG), LangChain, and Groq to provide intelligent responses based on uploaded documents.

Project Layout
The project is divided into three phases:

1. Setup UI for the Chatbot
Implement the chatbot interface using Streamlit.

Enable user interaction through the UI.

2. Connect to LLM
Utilize LangChain for managing interactions with the LLM (Large Language Model).

Leverage Groq as the LLM provider.

3. Integrate RAG
Upload and process documents (PDF, text, etc.).

Generate vector embeddings for efficient information retrieval.

Implement Retrieval-Augmented Generation (RAG) to enhance chatbot responses.

Tech Stack
Python

Streamlit (for UI)

LangChain (for LLM interaction)

Groq API (LLM provider)

FAISS / ChromaDB (for vector embeddings)

OpenAI/TensorFlow/PyTorch (optional for fine-tuning)

Installation & Setup
1. Clone the Repository
sh
Copy
Edit
git clone https://github.com/BadagiAnanya/Chatbot.git  
cd Chatbot
2. Install Dependencies using Pipenv
Ensure you have Pipenv installed. If not, install it using:

sh
Copy
Edit
pip install pipenv
Then, install project dependencies:

sh
Copy
Edit
pipenv install
3. Set Up Environment Variables
Create a .env file and add your API keys:

ini
Copy
Edit
GROQ_API_KEY=your_groq_api_key  
OPENAI_API_KEY=your_openai_api_key  
4. Run the Streamlit App
sh
Copy
Edit
pipenv run streamlit run model.py
Usage
Open the Streamlit UI in your browser.

Upload a document (PDF, text, etc.).

The chatbot will generate responses based on the document using RAG.

## **Deployed Model**  
You can use the deployed chatbot at:  
📌 [Chatbot Interface][([chatbot ∙ main ∙ Chatbot/model.py](https://chatbot-version01.streamlit.app/))](https://chatbot-version01.streamlit.app/)
