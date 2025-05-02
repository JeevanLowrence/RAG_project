# RAG_project
A fine-tuned, parametrized implementation of RAG system that supports document uploading using gradio.

## Model Used
We used a pre trained model LLama2 with 7 billion parameters as the LLM in the RAG pipeline.

## Quantization
Quantized the model to 4 bits before we start working on it.

## Processing documents uploaded by user - PyPDFLoader.

## Preprocessing
Chunking -> Creating Vector Database -> Getting Embeddings from Sentence transformers

## Prompt Injection
Modifying the prompt to align with the users needs, in this case it's question answering for medical domain.

## UI
Using gradio and interactive elements with real time status update on the processed pdfs.

## RAG System
Langchain to develop the rag system, setup retriever (choose optimal k value).

## Context Window
The LLM is provided recent chats from the conversation for understanding the context of the users queries and return tailored results.

## Future Work
Implementing Hybrid search with re-ranking models.
Multimodal retrieval for images/tables.
