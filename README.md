# METU IE Summer Practice Consultant Chatbot

An AI-driven digital consultant chatbot designed to assist METU Industrial Engineering students by streamlining queries related to summer practice rules, workflows, and documentation.

The system utilizes **Retrieval-Augmented Generation (RAG)**, structured **System Prompt Engineering**, and **Vector Embeddings** to deliver precise, context-aware guidance based on official department guidelines.

## Architecture of the Chatbot

* **Retrieval-Augmented Generation (RAG):** Integrates ChromaDB vector store to fetch accurate contextual information from embedded summer practice documentation.
* **System Prompt Engineering:** Implements strict system prompts and persona constraints to minimize hallucinations and enforce structured logic.
* **API Integration:** Connects with Large Language Model (LLM) APIs to generate natural language responses based on retrieved context.
* **Interactive Interface:** Provides a user-friendly conversational setup for student inquiry resolution.

## Tech Stack & Dependencies

* **Language:** Python 3.x
* **Vector Database:** ChromaDB (`chroma_db`)
* **AI/LLM Frameworks:** Gemini
* **Environment Management:** Python `dotenv`

## How to Run

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/keremberkeberber/METU-IE-Summer-Practice-Chatbot.git](https://github.com/keremberkeberber/METU-IE-Summer-Practice-Chatbot.git)
   cd METU-IE-Summer-Practice-Chatbot

2. Install dependencies & set up API key:
   pip install -r requirements.txt

3. Run the chatbot:
   python app.py
