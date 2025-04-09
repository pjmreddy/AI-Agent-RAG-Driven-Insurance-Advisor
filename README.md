<h1 align="center">AI-Agent RAG-Driven Insurance Advisor</h1>

An intelligent insurance advisory system powered by Retrieval Augmented Generation (RAG) technology. This project demonstrates multiple implementation approaches for building a context-aware AI agent that can provide accurate insurance-related information and assistance.

<h2 align="center">Project Overview</h2>

This project implements an AI-powered insurance advisory system using different RAG (Retrieval Augmented Generation) approaches:
- Traditional RAG implementation
- LangChain with Chroma vector store
- LangChain with FAISS vector store


<h2 align="center">Repository Structure</h2>

```
├── knowledge-base/           # Domain-specific knowledge
│   ├── company/             # Company information
│   ├── contracts/           # Insurance contracts
│   ├── employees/           # Employee profiles
│   └── products/            # Insurance products
├── vector_db/              # Vector database storage
└── *.ipynb                 # Implementation notebooks
```

<h2 align="center">Features</h2>

- Multiple RAG implementation approaches for comparison
- Comprehensive knowledge base covering:
  - Company information and overview
  - Insurance contracts and agreements
  - Employee profiles and expertise
  - Insurance product details
- Vector store integration with Chroma and FAISS
- Intelligent query processing and context retrieval
- Natural language understanding and response generation

<h2 align="center">Implementation Approaches</h2>

### 1. Traditional RAG Implementation
- Direct implementation of RAG architecture
- Custom context retrieval and processing
- Demonstrates core RAG concepts without additional frameworks

### 2. LangChain with Chroma
- Utilizes LangChain's document loading and processing
- Chroma vector store for efficient similarity search
- Enhanced context management through LangChain's abstractions

### 3. LangChain with FAISS
- FAISS vector store implementation
- High-performance similarity search
- Scalable vector storage and retrieval

<h2 align="center">Setup Instructions</h2>

1. Clone the repository
2. Install required dependencies:
   ```bash
   pip install langchain chromadb faiss-cpu openai
   ```
3. Create a `.env` file in the root directory:
   ```bash
   touch .env
   ```
4. Add your OpenAI API key to the `.env` file:
   ```
   OPENAI_API_KEY=your_api_key_here
   ```
5. Run the Jupyter notebooks to explore different implementations

<h2 align="center">Knowledge Base</h2>

The knowledge base is organized into four main categories:

1. **Company Information**
   - Company overview and background
   - Career opportunities
   - Corporate policies

2. **Insurance Contracts**
   - Detailed contract information
   - Terms and conditions
   - Partner agreements

3. **Employee Profiles**
   - Staff expertise and roles
   - Contact information
   - Departmental organization

4. **Insurance Products**
   - Product features and benefits
   - Coverage details
   - Pricing information

<h2 align="center">Vector Database</h2>

The project utilizes two vector store implementations:

1. **Chroma**
   - SQLite-based vector store
   - Efficient for smaller to medium-sized datasets
   - Easy to set up and maintain

2. **FAISS**
   - High-performance vector similarity search
   - Scalable for larger datasets
   - Optimized for fast retrieval

<h2 align="center">Usage</h2>

Each implementation approach is contained in its own Jupyter notebook:

- `RAG Agent in Traditional Way.ipynb`: Basic RAG implementation
- `LangChain RAG with Chroma Vector.ipynb`: Implementation using LangChain and Chroma
- `LangChain RAG with FAISS.ipynb`: Implementation using LangChain and FAISS

Open the notebooks to explore different approaches and their specific implementations.

<h2 align="center">Contributing</h2>

Contributions are welcome! Please feel free to submit a Pull Request.