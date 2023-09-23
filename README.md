# Understanding Themes in the Tech Industry in Different Phases of the Financial Cycle: A Topic Modelling Analysis of Academic Papers and Media Publications

## About this project

A fully functional project that uses BERTopic to:
1. Get themes researched in computer science during different stages of the economic cycle from January 2005- January 2023.
2. Get trending themes focused on by TechCrunch authors over the same period.
The code in this project shows how to do the following:
 
* Create document embeddings of research abstracts and news posts using sentence transformers
* Dimensionality reduction of these embeddings using UMAP
* Clustering the reduced embeddings using HDBSCAN
* Getting topics by fitting the trainsets, sentence transformer, UMAP and HDBSCAN models into BERTopic. We also use KeyBERTInspired to give the top 5 documents, and the top 10 words that best represent a HDBSCAN cluster. 
* Merging similar topics into one theme and assigning unique names to each theme.
* Evaluating the BERTopic Models
* 
![image](https://github.com/annm802/dissertation/assets/57720741/4dc146e8-2526-4027-b3eb-2db34a71c136)

# Getting Started
Install BERTopic dependencies

`import locale`

`locale.getpreferredencoding = lambda: "UTF-8"`

`!pip install cudf-cu11 dask-cudf-cu11 --extra-index-url=https://pypi.nvidia.com`

`!pip install cuml-cu11 --extra-index-url=https://pypi.nvidia.com`

`!pip install cugraph-cu11 --extra-index-url=https://pypi.nvidia.com`

`!pip install cupy-cuda11x -f https://pip.cupy.dev/aarch64`

Install project model dependencies

`!pip install -r requirements.txt`

