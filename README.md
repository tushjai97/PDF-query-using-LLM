# PDF-query-using-LLM
### Overview

This repository contains a demonstration project that integrates OpenAI's ChatGPT with Apache Cassandra, a NoSQL database, to enable querying and retrieving information from PDF documents. The main objective of this project is to explore how large language models (LLMs) like ChatGPT can be incorporated into applications to enhance data retrieval and processing capabilities.

### Project Description

This project utilizes the Langchain library to leverage the capabilities of ChatGPT for understanding and processing natural language queries. It then retrieves responses based on the content stored within a PDF document. The PDF content is pre-processed, converted into vector embeddings, and stored in Cassandra DB. This setup allows the application to perform efficient vector-based searches to find relevant information in response to user queries.

### Key Features

PDF Parsing: Extract text data from PDF documents and preprocess it for querying.
Vector Embeddings: Utilize state-of-the-art techniques to convert text data into vector embeddings that capture semantic meanings of the text.
Cassandra Database: Store and retrieve vector embeddings efficiently using Cassandra, a powerful NoSQL database known for its high availability and scalability.
Natural Language Queries: Process natural language queries using ChatGPT to understand user intent and fetch relevant information from the stored embeddings.
Technologies Used

Langchain: A library designed to bridge language models and applications, facilitating the integration of LLMs into various systems.

OpenAI's ChatGPT: A cutting-edge language model used for understanding and generating human-like text based on the input queries.

Apache Cassandra: A highly scalable NoSQL database that manages large volumes of data across multiple servers, providing high availability with no single point of failure.
