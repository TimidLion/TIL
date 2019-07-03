## tensorflow.nn.smapled_softmax_loss

```
tf.nn.sampled_softmax_loss(
    weights,
    biases,
    labels,
    inputs,
    num_sampled,
    num_classes,
    num_true=1,
    sampled_values=None,
    remove_accidental_hits=True,
    partition_strategy='mod',
    name='sampled_softmax_loss',
    seed=None
)
```

Used when, the number of classes is way too big.

Detailed algorithm : [candidate_sampling](https://www.tensorflow.org/extras/candidate_sampling.pdf)

This operation is for training only. It is generally an underestimate of the full softmax loss.
