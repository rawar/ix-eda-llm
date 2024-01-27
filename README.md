# Using large language models for exploratory data analysis

This repository contains examples of exploratory data analysis using large language models (LLMs). Open source tools such as Langchain, Vanna.ai, Pandas.ai and Cube are used to interact with data structures in natural language and thus make the use of SQL or the Pandas dataframe syntax obsolete. 

The paper [LIDA: A Tool for Automatic Generation of Grammar-Agnostic Visualizations and Infographics using Large Language Models](https://aclanthology.org/2023.acl-demo.11.pdf) from Microsoft Research shows how metadata and the schema description plus efficient prompting can be used to query data and even visualize it. Here you can easily understand the basic procedure of data in context (schema, DDL, samples, etc.) and the prompting towards the language model.

All examples use the [Northwind database](https://github.com/Microsoft/sql-server-samples/tree/master/samples/databases/northwind-pubs) as a basis.

The following files can be found in this repository:

* LIDA with Langchain [Notebook](https://github.com/rawar/ix-eda-llm/blob/main/lida-with-langchain.ipynb)
* Pandas.ai [Notebook](https://github.com/rawar/ix-eda-llm/blob/main/northwind_pandasai.ipynb)
* Langchain SQLDatabaseChain [Notebook](https://github.com/rawar/ix-eda-llm/blob/main/northwind_langchain.ipynb)
* Vanna.ai [Notebook](https://github.com/rawar/ix-eda-llm/blob/main/northwind_vanna_ai.ipynb)
* Cube [Notebook](https://github.com/rawar/ix-eda-llm/blob/main/northwind-cube.ipynb)

The Cube Notebbok can only run locally and requires Docker and the [docker-compose](https://github.com/rawar/ix-eda-llm/blob/main/docker-compose.yaml) file to build a local PostgreSQL instance with the Northwind database and the cube application.


