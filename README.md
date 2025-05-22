# Azure AI Search - Vector Search Samples

Este repositório contém exemplos de código com suporte a **vector search** no Azure AI Search. A funcionalidade está **geralmente disponível (GA)**, com alguns recursos ainda em **preview**, conforme os Termos Suplementares de Uso.

- ✅ **Indexação e consultas vetoriais**: Disponível (GA)
- 🧪 **Chunking de dados e vetorização integrada com indexers e skillsets**: Em preview

---

## 📁 Conteúdo

### Exemplos por linguagem e abordagem

| Sample | Linguagem | Descrição | Status |
|--------|-----------|-----------|--------|
| **DotNetVectorDemo** | .NET | Aplicativo console que usa Azure OpenAI para vetorização e Azure AI Search para criar, carregar e consultar dados vetoriais. | ✅ GA |
| **DotNetIntegratedVectorizationDemo** | .NET | App que cria index, indexer, fonte de dados e skillset. Usa Azure OpenAI durante a indexação e nas consultas. | 🧪 Preview |
| **JavaScriptVectorDemo** | JavaScript | Três exemplos: um completo com embeddings + indexação + consulta, e dois focados em geração de embeddings via Azure OpenAI. | ✅ GA |
| **demo-python/*.ipynb** | Python (Jupyter) | Notebooks com vetorização de texto e imagem, incluindo chunking. | ✅ GA / 🧪 Preview |
| **postman-collection** | REST (Postman) | Coleções REST API para versões GA (2023-11-01) e Preview (2023-10-01-preview). | ✅ GA / 🧪 Preview |

---

## 🚀 Aceleradores e Demos Relacionadas

| Nome | Descrição |
|------|----------|
| **[chat-with-your-data-solution-accelerator](https://github.com/Azure-Samples/azure-search-openai-demo)** | Template completo para criar uma solução de RAG com boas práticas. |
| **Azure Search OpenAI Demo** | App para RAG usando Azure AI Search + Azure OpenAI. Use o branch `vectors`. |
| **Azure Search OpenAI Demo - C#** | Versão em C# da demo anterior. |
| **Azure OpenAI Embeddings QnA with Azure Search** | App simples com Q&A baseado em embeddings e Azure Search. |
| **ChatGPT Retrieval Plugin + Azure Search** | Plugin oficial para buscar documentos usando Azure AI Search como vector DB. |
| **Azure Search Vector Search Demo Web App Template** | Template em React para busca vetorial (texto e imagem). |
| **Azure Cognitive Search Comparison Tool** | Ferramenta para comparar recursos do Azure AI Search. |

---

## 📚 Documentação Oficial

### Azure AI Search

- [Vector search overview](https://learn.microsoft.com/en-us/azure/search/vector-search-overview)
- [Hybrid search overview](https://learn.microsoft.com/en-us/azure/search/hybrid-search-overview)
- [Create a vector index](https://learn.microsoft.com/en-us/azure/search/vector-index-concept-overview)
- [Query a vector index](https://learn.microsoft.com/en-us/azure/search/vector-search-query-overview)
- [Vector search algorithms](https://learn.microsoft.com/en-us/azure/search/vector-search-algorithms)
- [RAG in Azure AI Search](https://learn.microsoft.com/en-us/azure/search/retrieval-augmented-generation-overview)
- [REST API Reference](https://learn.microsoft.com/en-us/rest/api/searchservice)

### Azure OpenAI Service

- [Azure OpenAI Service Documentation](https://learn.microsoft.com/en-us/azure/cognitive-services/openai/overview)

### Azure AI Vision

- [Azure AI Vision Documentation](https://learn.microsoft.com/en-us/azure/ai-services/computer-vision/overview)

---

> ⚠️ *Para os recursos em Preview, é necessário habilitar recursos específicos no portal do Azure ou usar APIs com versão preview.*
