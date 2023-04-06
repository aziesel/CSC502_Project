# CSC502_Project
Repository detailing the CSC502 project work conducted by Finn Archinuk, Ezra MacDonald and Alison Ziesel.

Index:


notebooks/apply_louvain_toy.ipynb: One of our implementations of the Louvain algorithm applied to the Les Misérables character interaction network. This implementation uses primitive types to define nodes, clusters and edges, and is partly implemented using PySpark dataframes.

notebooks/cluster_computations.ipynb: Explorations of Node and Cluster classes for our algorithm implementation, as well as the use of RDD versus Dataframe data structures.

notebooks/cu_graph_louvain.ipynb: Exploration of using the  Node and Cluster classes for our algorithm implementation.

notebooks/les_mis.py: Definition of the Les Misérables character interaction network. Network nodes are characters, edges are interactions weighted by the number of times those two characters interacted in the novel.

notebooks/louvain.ipynb: Explorations of Node and Cluster classes for our algorithm implementation, as well as the use of RDD versus Dataframe data structures.

notebooks/toy_network_and_data_preprocessing.ipynb: This notebook details the analysis of the Les Misérables network with the non-distributed 'python-louvain' library, as well as the preprocessing done to convert the ArXiv metadata into a coauthorship network.

CSC502 Presentation_Archinuk_MacDonald_Ziesel.pdf: a PDF version of our slides for the class presentation.
