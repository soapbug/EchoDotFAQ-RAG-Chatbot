# EchoDotFAQ — RAG FAQ Chatbot

This project is an FAQ chatbot built in Python using Retrieval-Augmented Generation (RAG).

## Tech Stack
- LangChain
- OpenAI embeddings + chat model
- ChromaDB vector store
- Pandas

## Files
- `echo_dot_faq_chatbot.py` — source code
- `EchoDotFAQ_StudyCom_Final_Submission_Sophia_Bugay.docx` — APA report
- `requirements.txt` — dependencies

## Run
1) Install dependencies: `pip install -r requirements.txt`  
2) Set your API key: `export OPENAI_API_KEY="..."`  
3) Run: `python echo_dot_faq_chatbot.py --reviews_csv <your_csv> --rebuild`
