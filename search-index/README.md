# Indexing and Searching
Implementation focuses on a specific library and showcases its capabilities for Search and Indexing applications.

### Setup Step by Step:
- create virtual enviroment using `virtualenv -p /path/to/python /path/to/venv`
- activate environment using `source /path/to/venv/activate`
- export Credntials if needed using `export VARIABLE_NAME="variable value"`
  - example: `export OZAI_API_CREDENTIALS="/path/to/user_cred.json"`
- If want to use ipython notebook start jupyter using `jupyter notebook .`
- Additionally you may install libraries using `pip install library_name`

#### Numpy Implementation
- The Numpy implementation illustrates how to perform indexing and searching using the Numpy library, a fundamental package for experimentation.
- Easy to understand and great to make you hand dirty to play with small datasets
- To explore the Numpy implementation, refer to the IPython notebook file: `Text Indexing using OzoneAI Embeding Numpy.ipynb`.

#### Faiss Implementation
- The Faiss implementation demonstrates the usage of the Faiss library for fast similarity search and indexing. Faiss is a widely adopted library for efficient similarity search and clustering of dense vectors.
- Easy to understand and great to make you hand dirty to play with medium to large datasets
- To explore the Faiss implementation, refer to the IPython notebook file: `Text Indexing using OzoneAI Embeding Faiss.ipynb`.

#### Milvus Implementation
- The Milvus implementation showcases how to use the Milvus library for efficient similarity search and vector indexing. Milvus is an open-source vector database that supports vector representation and similarity search for AI applications.
- Great to make you hand dirty to play with large datasets. This has good handle over CRUD operation.
- To explore the Milvus implementation, refer to the IPython notebook file: `Text Indexing using OzoneAI Embeding Milvus.ipynb`.

Note: These implementations are provided for experimental purposes and may not cover all advanced features or optimizations available in the libraries.