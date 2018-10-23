


<!-- DO NOT EDIT! Automatically generated file. -->
# tf.tanh

### `tf.nn.tanh`

```
tf.nn.tanh(x, name=None)
```

### `tf.tanh`

```
tf.tanh(x, name=None)
```


See the guide: [Neural Network > Activation Functions](../../../api_guides/python/nn#Activation_Functions)

Computes hyperbolic tangent of `x` element-wise.

#### Args:

* <b>`x`</b>: A Tensor or SparseTensor with type `float`, `double`, `int32`,
    `complex64`, `int64`, or `qint32`.
* <b>`name`</b>: A name for the operation (optional).


#### Returns:

  A Tensor or SparseTensor respectively with the same type as `x` if
  `x.dtype != qint32` otherwise the return type is `quint8`.

Defined in [`tensorflow/python/ops/math_ops.py`](https://www.tensorflow.org/code/tensorflow/python/ops/math_ops.py).
