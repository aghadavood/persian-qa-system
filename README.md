Persian Scientific Q&A System

Here are python files that deal with on-line question answering in Persian. The following files are thought of as more complete than the earlier ones.  As I progress through each stage, I face challenges that lead me to the next.


1. Gpt4api.ipynb - This is a conversational question-answering system designed for scientific Persian documents. It uses a combination of a vector database for document retrieval and OpenAI's language models to generate answers based on the retrieved content.
2. gradio_chat.ipynb -  interface with gradio

Features

Language Support: Persian (Farsi)
Document Retrieval: Uses FAISS for efficient similarity search
Embeddings Model: sentence-transformers/paraphrase-multilingual-MiniLM-L12-v2
Language Model: OpenAI's GPT-3.5-turbo (or GPT-4 if available)
Interface: Web-based interface using Gradio

Requirements

Python 3.7 or higher
An OpenAI API key

** whats the problem with this: 
it answer the questions but its not perfect at all i should try to improve.


**solutions:
Verify the relevance of retrieved documents.
Refine the prompt to guide the model effectively.
Use suitable embeddings models for Persian.
Increase the number of documents retrieved.
Ensure content length stays within token limits.
Consider using more capable models if available.
Enhance data quality and formatting.
Utilize advanced retrieval techniques with LangChain.
Provide few-shot examples in the prompt.
Adjust the temperature parameter for consistency.
Handle unknown answers appropriately.
Evaluate and iterate to improve performance.
Consider fine-tuning or using models with larger context windows.


