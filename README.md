# Community detection algorithms in Complex Networks
Communities are groups of nodes that are more densely connected to each other than to the rest of the network, and detecting them can be useful for understanding the underlying structure and function of complex networks.
This repository contains the community analysis of a connectome network, which is a network that contains a map of the neural connections in the brain, in this case obtained from MRI datasets of 477 people. In this network, nodes are brain regions and the edges can be weighted by several factors, although in this case they have been weighted by the fiber count mean. 

More specifically, in the attached report you will find a deep explanation and practical implementation of modularity based algorithms (Greedy and Louvain), as well as the probabilistic model named Stochastic Block Model.
This repository also contains the code used for the analysis, which was developed in Python using Google Collab and networkx library.

### Data source
The data used for the project can be downloaded from here:
https://networks.skewed.de/net/budapest_connectome#all_200k

### Acknowledgement
I would like to acknowledge my collegue, Linton Jones, who has contributed to the development of this project.

