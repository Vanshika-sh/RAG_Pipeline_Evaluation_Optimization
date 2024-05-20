# RAG_Pipeline_Evaluation_Optimization
### Project Description

This project focuses on the evaluation of Retrieval-Augmented Generation (RAG) applications. It involves building a comprehensive pipeline that integrates document indexing, query handling, and evaluation metrics to assess the performance of RAG systems.

#### Key Functionalities

1. **Document Indexing**: 
    - Uses `vector_indexing` function to create an index from documents.
    - Employs OpenAI's GPT-3.5 model for generating embeddings.

2. **Query Handling**: 
    - Uses `query_index` function to handle user queries and retrieve relevant information from indexed documents.

3. **Evaluation Metrics**: 
    - Uses `eval_basic_rag` function to assess the performance of the RAG application.
    - Evaluates responses using metrics like Answer Relevance, Context Relevance, and Question Relevance.

4. **Advanced Indexing Techniques**:
    - Uses `build_automerging_index` function to implement automerging for efficient retrieval.
    - Breaks down documents into chunks, applies hierarchical parsing, and stores nodes for optimized querying.

#### Usage

1. **Document Indexing**: 
    - Call `vector_indexing(document)` to create an index from the provided document.

2. **Query Handling**: 
    - Call `query_index(index, query)` to retrieve information based on the user query.

3. **Evaluation**: 
    - Define evaluation questions and call `eval_basic_rag(query_engine, eval_questions)` to assess the performance.

4. **Advanced Indexing**: 
    - Call `build_automerging_index(documents, llm)` to create an advanced automerging index for efficient retrieval.

#### Requirements

- OpenAI API key
- Dependencies: `llama_index`, `trulens_eval`, `streamlit`, `datasets`, `ragas`
``` &#8203;``【oaicite:0】``&#8203;
