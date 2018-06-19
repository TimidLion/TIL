## tensor.Tensor.backward function

Computes the gradient of current tensor w.r.t. graph leaves.

The graph is differentiated by chain rule. 
If the tensor is non-scalar (i.e. its data has more than one element) and requires gradient, the function additionally requires specifying gradient.
It should be a tensor of matching type and location, that contains the gradient of the differentiated function w.r.t. self.

This function accumulates gradients in the leaves - you might need to zero them before calling it.
