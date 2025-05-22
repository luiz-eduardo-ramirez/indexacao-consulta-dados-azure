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
| **JavaScriptVectorDemo** | JavaScript | Três exemplos: um completo com embeddings + indexação + consulta, e dois focados em geração de embedding
