# Multiple-PDF-Chat


The **MultiPDF Chat App** is a Python application that allows you to chat with multiple PDF documents using natural language. You can ask questions, and the app will provide accurate, context-aware responses based on the content of the loaded PDFs. This project leverages a language model to process and answer your queries intelligently.

---

## 🔧 Tech Stack
- **Python** for backend processing
- **PyPDF** for PDF content extraction
- **FAISS** for vector similarity search
- **OpenAI API** for generating conversational answers
- **Streamlit** for building the web app


## 📌 Features
- Upload multiple PDFs at once
- Extracts and chunks PDF content for semantic indexing
- Generates vector embeddings for efficient search
- Retrieves relevant chunks using FAISS similarity search
- Provides accurate answers using OpenAI's GPT model
- Clean and interactive UI using Streamlit

## How to Run?
### STEPS:


```bash
   #Clone the repository
   git clone: https://github.com/mssahana01/Multiple-PDF-Chat.git
```


```bash
    # Install the dependencies
    pip install -r requirements.txt
```

```bash
    #Set your OpenAI API key
    OPENAI_API_KEY=your_secret_key
```

```bash
    #Run the Streamlit app
    streamlit run app.py
```