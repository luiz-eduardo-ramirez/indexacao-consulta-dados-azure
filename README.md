Vector search samples - Azure AI Search

This repository has code samples for vector support in Azure AI Search. Vector search is generally available, but it also has capabilities still in preview, under Supplemental Terms of Use.

    Vector indexing and queries are generally available.
    Integrated data chunking and vectorization, which takes a dependency on indexers and skillsets, is in preview.

Content
Sample 	Description 	Status
DotNetVectorDemo 	A .NET console app that calls Azure OpenAI to vectorize data. It then calls Azure AI Search to create, load, and query vector data. 	Generally available (GA)
DotNetIntegratedVectorizationDemo 	A .NET console app that calls Azure AI Search to create an index, indexer, data source, and skillset. An Azure Storage account provides the data. Azure OpenAI is called by the skillset during indexing, and again during query execution to vectorize text queries. 	Public preview
JavaScriptVectorDemo 	There are three code samples. One is an end-to-end code sample that calls Azure OpenAI for embeddings and Azure AI Seach to create, load, and query an index that contains vectors. Another sample calls just Azure OpenAI and is used to generate embeddings for fields in an index. The last one also calls just Azure OpenAI and is used to generate an embedding for a vector query. 	GA
demo-python/*.ipynb 	A collection of notebooks that demonstrate aspects of vector search, including data chunking and vectorization of both text and image content. 	GA and preview
postman-collection 	Two separate Postman collections of REST API calls for generally available (2023-11-01) and preview (2023-10-01-preview) versions. GA version shows you how to create, load, and query vector and non-vector content in an index. Preview version demonstrates integrated data chunking and vectorization through indexers and skillsets. Use the Postman app for these samples. 	GA and preview
Related samples and tools

    chat-with-your-data-solution-accelerator A template that deploys multiple Azure resources for a custom chat-with-your-data solution. Use this accelerator to create a production-ready solution that implements coding best practices.
    Azure Search OpenAI Demo A sample app for the Retrieval-Augmented Generation pattern running in Azure, using Azure AI Search for retrieval and Azure OpenAI large language models to power ChatGPT-style and Q&A experiences. Use the "vectors" branch to leverage Vector retrieval.
    Azure Search OpenAI Demo - C# A sample app for the Retrieval-Augmented Generation pattern running in Azure, using Azure AI Search for retrieval and Azure OpenAI large language models to power ChatGPT-style and Q&A experiences using C#.
    Azure OpenAI Embeddings QnA with Azure Search as a Vector Store (github.com) A simple web application for a OpenAI-enabled document search. This repo uses Azure OpenAI Service for creating embeddings vectors from documents. For answering the question of a user, using Azure AI Search for retrieval and Azure OpenAI large language models to power ChatGPT-style and Q&A experiences.
    ChatGPT Retreival Plugin Azure Search Vector Database The ChatGPT Retrieval Plugin lets you easily find personal or work documents by asking questions in natural language. Azure AI Search now supported as an official vector database.
    Azure Search Vector Search Demo Web App Template A Vector Search Demo React Web App Template using Azure OpenAI for Text Search and Cognitive Services Florence Vision API for Image Search.
    Azure Cognitive Search Comparison Tool

Documentation

Azure AI Search Documentation

    Retrieval Augmented Generation (RAG) in Azure AI Search
    Vector search overview
    Hybrid search overview
    Create a vector index
    Query a vector index
    Vector search algorithms
    REST API reference

Azure OpenAI Service Documentation

Azure AI Vision Documentatio
