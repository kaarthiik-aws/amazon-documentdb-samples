# Code samples of vector search for Amazon DocumentDB

## Chatbot Demo using vector search for Amazon DocumentDB
- File Name: [docdb_ivfflat_rag](https://github.com/aws-samples/amazon-documentdb-samples/blob/master/samples/vector-search/docdb_ivfflat_rag.ipynb)
- Notedbook was tested using python 3.8, langchain  0.1.0, pymongo 4.6.1, gradio 4.14.0
- Uses Amazon DocumentDB as vector store with IVFFlat index type 
- Uses Langchain and third party (Open AI) embedding and LLM model. User will need an Open AI key.
- Dataset: You could use this [sample transcript from The Motley Fool](https://github.com/aws-samples/amazon-documentdb-samples/blob/master/samples/vector-search/sample-datasets/transcript.txt) for the demo