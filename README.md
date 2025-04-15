These python notebooks document my learnings in constructing a Retrieval Augmented Generator to sumamrise research papers. 

- The Langchain framework was used to construct each element of the RAG model.
- Relevant documents (PDFs) were sourced via the arXiv API.
- PDFs were read, chunked and stored as embedded vectors in vector stores. Metadata was added prior to embedding to improve semantic search retrieval.
- A number of LLM models were tested, and prompt engineering was used to improve the response when combined with retreived information.

- Next steps involve testing and monitoring the model to improve each step.
