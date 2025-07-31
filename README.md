# Tutor ChatBot based on RAG System


## System

### Indexer

1. Receive course notes as a text file
2. Chunking text using character text splitter
3. Text embedding and create vector database
  
### Responder

1. Recive query as a free text
2. Retrieve relevant information with semantic similarity search 
3. Putting the query and context in a prompt template
4. Response generation by LLM

### Technologies

- **RAG system:** [LangChain](https://www.langchain.com/)
- **Vector database:** FAISS 
- **Embedding model:** [sentence-transformers/paraphrase-multilingual-MiniLM-L12-v2](https://huggingface.co/sentence-transformers/paraphrase-multilingual-MiniLM-L12-v2)
- **Generator LLM:** [Gemma3:12b based on Ollama](https://ollama.com/library/gemma3)
