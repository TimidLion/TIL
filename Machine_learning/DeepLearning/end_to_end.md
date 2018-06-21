## end-to-end
  
The learning that optimizes the network weights by considering the inputs and outputs directly is called end-to-end learning. 

ex) 

**end-to-end** : The convolutional neural network to map raw pixels from a camera directly to steering commands in [1]

**not end-to-end** : a neural network may contain too many layers of nodes to fit into memory. One possible solution is to divide the network into a pipelin    e of smaller networks. Each small network can be trained independently and t    hen connected to obtain desired output. 

[1] *Bojarski, Mariusz, et al. "End to End Learning for Self-Driving Cars." arXiv preprint arXiv:1604.07316 (2016).*
