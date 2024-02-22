# Lab 3 - Getting started with VSS
Duration: 30 mins

In this lab, you are going to run the SageMaker Jupyter Notebook to learn on how to do the following:
- Generating vector embeddings for text data using SentenceTransformers.
- Storing JSON documents containing text and vector embeddings in Redis.
- Creating a RediSearch index on the JSON data.
- Performing semantic searches using vector similarity queries.
- Query types demonstrated:
  - KNN similarity search
  - Hybrid search using filters
  - Range queries

The notebook includes code and examples using a synthetic dataset of bicycle descriptions.

## Steps

1. Configure Redis Enterprise Cloud endpoint details, by clicking on the line that has .
   
![](images/vss-1.png)

2. Replace the `host`, `port` and `password` details with the database endpoint details which you received from the lab spreadsheet.

```
host = ???
port = ????
password = '??????????????????????????'
```
After replacing the Redis Enterprise database endpoint credentials, it will look like this:

![](images/vss-2.png)

4. You can simply hit `Run` ==> `Run All Cells` or you can run each cell one by one while learning the nuances of doing VSS on Redis.
   
![](images/vss-4.png)

5. Happy running the entire code and learning more...
   
![](images/vss-5.png)

[<< Previous Lab (2) <<](../Lab&#32;2&#32;-&#32;Redis&#32;Enterprise&#32;Cloud&#32;Setup) | [>> Next Lab (4) >> ](../Lab&#32;4&#32;-&#32;Cleanup)
