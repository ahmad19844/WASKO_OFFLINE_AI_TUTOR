Architecture Decisions
Project Overview

Wasko AI Tutor is an offline AI-powered educational platform designed to provide students with access to learning materials in Cybersecurity, Networking, Digital Forensics, Artificial Intelligence, Digital Marketing, and related ICT fields without requiring an internet connection.

The system uses Retrieval-Augmented Generation (RAG) to answer questions from a local knowledge base while maintaining complete offline functionality.

Why Python?

Python was selected as the primary programming language because:

Simple and readable syntax
Large AI and Machine Learning ecosystem
Extensive support for Natural Language Processing (NLP)
Excellent integration with LLM frameworks
Cross-platform compatibility (Windows, Linux, macOS)
Rapid development and prototyping

Python enables quick integration of AI models, vector databases, and user interfaces within a single ecosystem.

Why Streamlit?

Streamlit was chosen as the user interface framework because:

Fast development of interactive web applications
Minimal frontend coding required
Easy deployment on local machines
Lightweight and beginner-friendly
Supports file uploads and document viewing
Suitable for educational applications

Streamlit allows students and instructors to interact with the AI tutor through a simple browser-based interface.

Why llama.cpp?

llama.cpp was selected as the inference engine because:

Runs Large Language Models completely offline
Optimized for CPU-based systems
Low memory consumption
Supports quantized models for faster performance
Cross-platform support
No cloud dependency

The project aims to serve schools and students in areas with limited internet connectivity. llama.cpp enables efficient local execution of AI models without requiring expensive hardware.

Why Phi-3 Mini?

Phi-3 Mini was selected as the default language model because:

Small memory footprint
Fast inference speed
Good reasoning capabilities
Optimized for local deployment
Suitable for educational question answering
Performs well on devices with 8GB RAM

The model provides a balance between performance, resource usage, and accuracy.

Why ChromaDB?

ChromaDB was selected as the vector database because:

Lightweight architecture
Fully offline operation
Easy integration with Python
Fast similarity search
Minimal setup requirements
Open-source and free

ChromaDB stores embeddings of educational materials and retrieves relevant content during question answering.

Why Retrieval-Augmented Generation (RAG)?

RAG was selected because:

Improves answer accuracy
Reduces hallucinations
Uses trusted local knowledge sources
Supports domain-specific educational content
Enables offline knowledge retrieval
Allows easy expansion of learning materials

Instead of relying solely on the language model, the system first retrieves relevant information from local documents and then generates responses based on that content.
