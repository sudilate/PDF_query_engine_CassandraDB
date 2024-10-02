Implementation of an PDF query engine with the help of Cassandra DB (Astra DB) which is an open source database to store vector embeddings and help in query retrieval process.
OpenAI embeddings are used to embedd the pdf which is read through **PyPDF2** module object.
Astra DB is intitalised with the help of **cassio**.
Once the data which is read through pdf object it is converted into vector emebeddings and stored in Cassandra DB in Cloud with help of AstraDB.
