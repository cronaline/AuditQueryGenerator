# AuditQueryGenerator

## General info
As we need to prove that our ingestion processes write information with quality and the ingestion processes write statistics into a particular table. To prove that the ingestion processes achieve the requiered quality levels we need to execute some queries and obtaine screenshots of their execution.

This project contains two different jupyter notebooks to carry out this.

- **_GeneradorCifrasAuditoria.ipynb_** : which takes as parameters which tables we are going to analize, and which quality rules we are checking. 
   As we need to take some screenshots as evidence of the execution of this queries, it generates a new notebook with code written in Scala and spark. Which contains all the requiered queries
   It is written in Python using the jupyter's notebook API
   
- **_auditoria_notebook.ipynb_** : This notebook is created after the execution of GeneradorCifrasAuditoria.ipynb and contains all requiered queries.
   This notebook contains code written in Scala and Spark

## Technologies
- Python 3
- Scala 2.9
- Spark 2.4

## Sources
- [Stackoverflow](https://stackoverflow.com/questions/38193878/how-to-create-modify-a-jupyter-notebook-from-code-python/45672031)
