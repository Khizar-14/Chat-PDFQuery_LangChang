Chat with PDF using Gemini 💁
This Streamlit application allows users to interactively query PDF documents using Google's Gemini model. The application extracts text from uploaded PDFs, creates embeddings using Google Generative AI, and performs similarity searches to answer user questions based on the content of the PDFs. It leverages the power of FAISS for efficient vector search and provides detailed answers using a custom-built conversational chain.

Features
PDF Text Extraction: Upload multiple PDF files and extract their text content.
Text Chunking: Split the extracted text into manageable chunks for efficient processing.
Vector Store Creation: Create and store text embeddings using Google Generative AI, and manage them with FAISS.
Conversational Q&A: Ask questions about the content of the uploaded PDFs, and receive detailed answers based on the context provided in the documents.
Streamlit Interface: User-friendly web interface for easy interaction.
