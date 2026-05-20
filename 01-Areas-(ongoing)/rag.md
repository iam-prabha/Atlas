# Retrieval Augmented Generation (RAG)

- The rag solve the problem of large language model's fixed memory what it trained on.
- It gives an ai ability to find relevant information to large language model (llm) to answer more accurate and avoid hallucations.

# standard rag workflow

- Input - asking a question to system.
- Indexing - tasks a bunch of document into smaller pieces of chunks, and turn into format the computer search quickly (called vector).
- Retrieval - compares the question that i ask against index and grabs a relevant documents.
- Generation - finally the system feeds the question i ask and retrieve documents combines that to answer my questions.

> The problem: basic workflow is struggling to retrieve right information or missing facts.

# Advanced Rag

- Before hand down documents to ai it improves quality of search as tool itself and organizes database better.
# Modular Rag

- It easy add or remove like toy blocks similar to search engine/ memory unit that fits perfectly for the problem they solve.
