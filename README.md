# MLSAF_Project
## ML Security and Fairness Project

Implementation of the method proposed in the paper:
Adversarial Attacks on Neural Networks for Graph Data

by Daniel Zügner, Amir Akbarnejad and Stephan Günnemann.
Published at SIGKDD'18, August 2018, London, UK

Copyright (C) 2018
Daniel Zügner
Technical University of Munich

This implementation is written in Python 3 and uses Tensorflow for the GCN learning.

Requirements
numpy
scipy
scikit-learn
matplotlib
tensorflow
numba

Installation
python setup.py install

Run the code
To try our code, you can use the IPython notebook demo.ipynb.

Example output


References
Datasets
In the data folder we provide the following datasets originally published by

Cora
McCallum, Andrew Kachites, Nigam, Kamal, Rennie, Jason, and Seymore, Kristie.
Automating the construction of internet portals with machine learning.
Information Retrieval, 3(2):127–163, 2000.

and the graph was extracted by

Bojchevski, Aleksandar, and Stephan Günnemann. "Deep gaussian embedding of
attributed graphs: Unsupervised inductive learning via ranking." ICLR 2018.

Citeseer
Sen, Prithviraj, Namata, Galileo, Bilgic, Mustafa, Getoor, Lise, Galligher, Brian, and Eliassi-Rad, Tina.
Collective classification in network data.
AI magazine, 29(3):93, 2008.

PolBlogs
Lada A Adamic and Natalie Glance. 2005. The political blogosphere and the 2004
US election: divided they blog.
In Proceedings of the 3rd international workshop on Link discovery. 36–43.

Graph Convolutional Networks
Our implementation of the GCN algorithm is based on the authors' implementation, available on GitHub here.

The paper was published as

Thomas N Kipf and Max Welling. 2017.
Semi-supervised classification with graph convolutional networks. ICLR (2017).
