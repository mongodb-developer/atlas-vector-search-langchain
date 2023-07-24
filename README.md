# How to Integrate LangChain with MongoDB Atlas Vector Search to realise the true potential of Retrieval Augmented Generation
This Repo shows how to integrate LangChain, Open AI and store embeddings in the MongoDB Atlas and run a similarity search using MongoDB Atlas Vector Search.

## The Notebook shows how to 
- create a vector search index using the MongoDB Atlas GUI and
- how can we store vector embeddings in MongoDB documents create a vector search index using the MongoDB Atlas GUI
- perform KNN search using Approximate Nearest Neighbors algorithm which uses the Hierarchical Navigable Small World (HSNW) graphs

and also throws some light on
- Comparing textual and fuzzy search with semantic search

   ![image](https://github.com/mongodb-developer/atlas-vector-search-langchain/assets/25996527/96e8408f-b974-472c-bdef-ca8d5246230a)

  ![image](https://github.com/mongodb-developer/atlas-vector-search-langchain/assets/25996527/46dccc72-b1de-4920-9507-70c799cdbe9a)


- LLM without the retrieval architecture

  ![image](https://github.com/mongodb-developer/atlas-vector-search-langchain/assets/25996527/6e8bcb24-5246-4096-a822-9bfa7337854e)

- How retrieval architecture helps when we create vector embeddings and do a vector similarity search using MongoDB Atlas Vector Search 

![image](https://github.com/mongodb-developer/atlas-vector-search-langchain/assets/25996527/6b666534-56b3-49d9-ab24-b12fe16a31f6)

## Tools used
Google colab 

  ## References
  - [MongoDB Atlas Vector Search](https://www.mongodb.com/products/platform/atlas-vector-search)
  - [MongoDB Documentation for Indexing vector embeddings](https://www.mongodb.com/docs/atlas/atlas-search/field-types/knn-vector/)
  - [MongoDB Gen AI Whitepaper](https://www.mongodb.com/collateral/embedding-generative-ai)
  - [MongoDB Blog](https://www.mongodb.com/blog/post/going-from-zero-to-one-enterprise-ready-mongodb-llms)
  - [LangChain Integration with MongoDB](https://python.langchain.com/docs/modules/data_connection/vectorstores/integrations/mongodb_atlas)

