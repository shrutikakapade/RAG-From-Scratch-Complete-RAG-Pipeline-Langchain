<h1>Retrieval-Augmented Generation (RAG) From Scratch</h1>

<p>
This repository provides a structured and practical guide to understanding and 
implementing <b>Retrieval-Augmented Generation (RAG)</b> using modern AI tools 
such as LangChain.
</p>

<p>
The goal of this project is to help students, developers, and AI practitioners 
learn how to build a complete RAG pipeline step-by-step, starting from the 
fundamental components and progressing toward a fully functional system.
</p>

<hr>

<h2>What is Retrieval-Augmented Generation (RAG)?</h2>

<p>
Retrieval-Augmented Generation (RAG) is an AI architecture that enhances the 
capabilities of Large Language Models (LLMs) by integrating external knowledge 
retrieval mechanisms.
</p>

<p>
Instead of relying only on the information stored in a pre-trained model, 
RAG retrieves relevant information from external data sources such as 
documents, databases, or web pages and provides that context to the model 
during response generation.
</p>

<p>
This significantly improves the accuracy, reliability, and relevance of 
generated responses.
</p>

<hr>

<h2>Why RAG is Important</h2>

<ul>
<li>Enables LLMs to access <b>external knowledge sources</b></li>
<li>Reduces <b>hallucinations</b> in generated responses</li>
<li>Supports <b>domain-specific knowledge systems</b></li>
<li>Allows AI systems to work with <b>private datasets</b></li>
<li>Improves the <b>accuracy and trustworthiness</b> of AI applications</li>
</ul>

<hr>

<h2>Core Components of a RAG Pipeline</h2>

<p>
A typical RAG system consists of several modular components that work 
together to retrieve relevant information and generate accurate responses.
</p>

<ol>
<li>Document Loader</li>
<li>Text Splitter</li>
<li>Embedding Model</li>
<li>Vector Database</li>
<li>Retriever</li>
<li>Large Language Model (LLM)</li>
<li>Response Generation</li>
</ol>

<hr>

<h2>RAG System Workflow</h2>

<p>
The complete workflow of a Retrieval-Augmented Generation system typically 
follows these steps:
</p>

<ol>
<li>Load raw data from different sources such as PDFs, websites, CSV, or JSON files.</li>
<li>Split large documents into smaller manageable chunks.</li>
<li>Convert text chunks into vector embeddings using embedding models.</li>
<li>Store embeddings in a vector database.</li>
<li>Retrieve the most relevant chunks based on a user query.</li>
<li>Provide retrieved context to the LLM.</li>
<li>Generate an accurate response using both retrieved knowledge and model reasoning.</li>
</ol>

<hr>

<h2>Repository Structure</h2>

<p>
This repository is designed as a progressive learning resource where each 
module focuses on one component of the RAG pipeline.
</p>

<ul>
<li>Document Loaders</li>
<li>Text Splitters</li>
<li>Embeddings</li>
<li>Vector Databases</li>
<li>Retrievers</li>
<li>Complete End-to-End RAG Pipeline</li>
</ul>

<hr>

<h2>📚 Notebook Overview – RAG Pipeline Implementation</h2>

<p>
This section provides a concise overview of each notebook, covering the complete 
<b>Retrieval-Augmented Generation (RAG) pipeline</b> from data ingestion to vector storage and retrieval.
</p>

<hr>

<ul>

  <li>
    <b>langchain_document_loaders_unstructured_practical_examples.ipynb</b>
    <ul>
      <li>Implements multiple LangChain document loaders (Web, CSV, JSON, Unstructured)</li>
      <li>Demonstrates multi-source data ingestion</li>
      <li>Prepares raw data for RAG pipeline processing</li>
    </ul>
  </li>

  <br>

  <li>
    <b>01_rag_pdf_document_loaders_langchain_examples.ipynb</b>
    <ul>
      <li>Focuses on PDF data extraction using different loaders</li>
      <li>Compares PyPDFLoader, PyMuPDFLoader, and UnstructuredPDFLoader</li>
      <li>Handles complex formats like images, Word, and PowerPoint files</li>
    </ul>
  </li>

  <br>

  <li>
    <b>Text_splitters_in_RAG_Pipeline.ipynb</b>
    <ul>
      <li>Explains text splitting in RAG systems</li>
      <li>Breaks large documents into smaller chunks</li>
      <li>Improves LLM performance and retrieval accuracy</li>
    </ul>
  </li>

  <br>

  <li>
    <b>RAG_Retriever_Search.ipynb</b>
    <ul>
      <li>Implements loading, splitting, and embedding steps</li>
      <li>Converts text into vector embeddings</li>
      <li>Enables semantic similarity-based retrieval</li>
    </ul>
  </li>

  <br>

  <li>
    <b>rag_multi_model_embeddings_faiss_ipynb.ipynb</b>
    <ul>
      <li>Builds an end-to-end RAG pipeline</li>
      <li>Uses OpenAI, Gemini, and Hugging Face embeddings</li>
      <li>Integrates FAISS for fast vector search</li>
      <li>Explores EUCLIDEAN and COSINE similarity strategies</li>
    </ul>
  </li>

  <br>

  <li>
    <b>huggingface_embeddings_to_chroma_vector_db.ipynb</b>
    <ul>
      <li>Uses HuggingFaceEmbeddings (MiniLM) for semantic search</li>
      <li>Creates structured Document objects</li>
      <li>Builds Chroma vector database using from_documents()</li>
      <li>Performs CRUD operations on vector data</li>
    </ul>
  </li>

</ul>

<hr>
<h2>Who Should Use This Repository?</h2>

<ul>
<li>Students learning Generative AI</li>
<li>Developers building AI applications</li>
<li>Engineers exploring LangChain</li>
<li>Anyone interested in learning how RAG systems work</li>
</ul>

<hr>

<h2>Project Objective</h2>

<p>
The objective of this repository is to provide a clear, structured, and 
practical learning path for building Retrieval-Augmented Generation systems 
from scratch using modern AI frameworks.
</p>

<p>
By following this repository, readers will gain both conceptual understanding 
and practical implementation experience required to develop real-world 
RAG-based AI applications.
</p>
