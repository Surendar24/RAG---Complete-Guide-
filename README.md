# RAG (Retrieval-Augmented Generation) Project

A comprehensive implementation of Retrieval-Augmented Generation (RAG) with various components and configurations.

## Project Structure

```
RAG/
├── Agentic AI and Multi Modal RAG/     # Multi-modal RAG implementations
├── Agentic RAG/                       # Agent-based RAG approaches
├── Agents Architecture/               # Architecture designs for RAG agents
├── Autonomous RAG/                    # Self-contained RAG implementations
├── Chunking and searching/            # Text chunking and search strategies
├── Data ingestion and parsing/        # Data loading and preprocessing
├── End to End Rag Document Search Project/  # Complete document search implementation
├── GraphDB RAG/                       # Graph database implementations
├── Langchain Basics/                  # Fundamental LangChain examples
├── Query Enhancement/                 # Query processing and optimization
├── RAG Eval with llm as judge with langsmith/  # Evaluation frameworks
├── Types of RAG/                      # Different RAG architectures
├── Vector embeddings/                 # Embedding generation and management
├── Vector stores and DB/              # Vector database implementations
├── ENV.env                           # Environment variables
└── requirements.txt                  # Python dependencies
```

## Prerequisites

- Python 3.8+
- Git
- Virtual environment (recommended)

## Installation

1. Clone the repository:

   ```bash
   git clone <repository-url>
   cd RAG
   ```

2. Create and activate a virtual environment:

   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

4. Set up environment variables:
   - Copy `ENV.env` to `.env` and update with your API keys
   - Required API keys:
     - OpenAI API key
     - Groq API key (if using Groq models)

## Usage

1. Navigate to the specific implementation you're interested in, for example:

   ```bash
   cd "End to End Rag Document Search Project"
   ```

2. Run the Jupyter notebook or Python script:
   ```bash
   jupyter notebook
   # or
   python your_script.py
   ```

## Key Components

### Data Ingestion

- Handles various document formats (PDF, DOCX, TXT, etc.)
- Text extraction and preprocessing
- Data cleaning and normalization

### Vector Stores

- FAISS for efficient similarity search
- ChromaDB for vector storage
- Support for multiple embedding models

### RAG Types

- Basic RAG implementations
- Advanced agent-based RAG
- Multi-modal RAG capabilities

### Query Processing

- Query expansion and enhancement
- Context-aware retrieval
- Response generation with LLMs

## License

MIT License - see the LICENSE file for details.
