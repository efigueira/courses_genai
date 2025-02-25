# LangChain - Chat with Your Data (DeepLearning.ai)  

This directory contains notes, code, and resources from the **LangChain - Chat with Your Data** course by DeepLearning.ai.

## 📝 Course Overview  

This course, created in collaboration with Harrison Chase (co-founder of LangChain), teaches how to build applications that allow users to interact with their own datasets using Large Language Models (LLMs).  

## 📂 Directory Structure  

```
├── latex/                   # LaTeX files for generating the course notes  
│   ├── images/              # Figures and diagrams used in the document  
│   ├── lc_chat_with_your_data.tex  # LaTeX source  
│   └── sample.bib           # Bibliography file  
├── src/                     # Jupyter notebooks and scripts  
│   ├── 01_document_loading/  
│   ├── 02_document_splitting/  
│   ├── 03_vectorstores_and_embeddings/  
│   ├── 04_retrieval/  
│   ├── 05_question_answering/  
│   ├── 06_chat/  
│   ├── docs/                # Additional resources  
│   ├── prep_ffmpeg.sh       # Setup script  
│   ├── requirements.txt     # Dependencies  
└── README.md                # Course-specific README  
```

## 📚 Topics Covered  

1. **Introduction**  
   - Understanding LLMs  
   - Introduction to LangChain and its core components  

2. **Document Handling**  
   - Loading structured & unstructured data (PDFs, YouTube transcripts, web pages, Notion data)  
   - Document splitting strategies  

3. **Vector Stores & Embeddings**  
   - Creating embeddings for efficient search  
   - Storing data in vector databases  

4. **Advanced Retrieval Techniques**  
   - Semantic search  
   - Maximum Marginal Relevance (MMR)  
   - LLM-assisted retrieval  
   - Contextual compression  

5. **Building a Chatbot with LangChain**  
   - Question-answering using retrieved documents  
   - Handling context windows  
   - Integrating chat history for a conversational AI  

## 📖 Notes  

- The full course notes are available in `latex/lc_chat_with_your_data.tex`.  
- Each section has an accompanying Jupyter notebook under `src/`, containing practical implementations.  

## 🛠️ Running the Notebooks  

To run the notebooks, install dependencies using:  

```bash
pip install -r requirements.txt
```

Then, start Jupyter Notebook:  

```bash
jupyter notebook
```

## 📌 Future Work  

- Experimenting with different document loaders  
- Enhancing retrieval mechanisms for improved accuracy  
- Implementing additional memory mechanisms in the chatbot