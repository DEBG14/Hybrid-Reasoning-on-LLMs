#  Exploring Hybrid Reasoning with Knowledge graphs in LLMs
This repository contains the development and testing of a Graph informed RAG as part of my M.Sc. research project, conducted under the supervision of [Dr. B. S. Panda](https://scholar.google.co.in/citations?user=ZwgtvXIAAAAJ&hl=en), IIT Delhi, from January 2024 to May 2024. The research focuses on the "Retreval" of Retrieval-Augmented Generation (RAG) by incorporating knowledge graph reasoning to explore the potential benefits of structured knowledge representations in improving the quality and relevance of responses in complex, relationship rich datasets for question answering tasks.


# Introduction
Retrieval-Augmented Generation (RAG) is a framework that combines retrieval mechanisms with large language models to improve the contextual relevance of generated responses. This project explores the integration of knowledge graphs (KGs) to enhance context structuring by leveraging reasoning capabilities inherent to graph-based representations. Knowledge graphs transform unstructured data into structured data, enabling deeper insights and more accurate retrieval.

Although this research focuses on exploration rather than evaluation, the goal is to understand how knowledge graphs can contribute to:

* Structuring context for more coherent and precise answers.
* Modeling complex relationships and dependencies in datasets.

# Key Features
* Datasets: Includes publicly available sources like Wikipedia and  legal interogation datasets for question-answering tasks.
* Knowledge Graph Construction: Transform unstructured data into structured knowledge graphs using graph transformers.
* Enhanced Retrieval: Use graph-based reasoning with Cypher queries for more accurate context retrieval.
* RAG Integration: Combine retrieved knowledge graph information with LLMs to generate enhanced answers using better reasoning paths.


# Usage
* Test and run the project seamlessly using the provided Colab notebook integrated with Neo4j and Mistral APIs. Make sure to enter your own api keys. 
* Feed your own PDF files in file section in colab for knowledge graph construction and testing or use the PDF files given and the Wikipedia dataset in the notebook.

  

