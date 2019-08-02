### Matrix Product
```python
import tensorflow as tf

x = tf.placeholder(tf.float32, (None, 10))
w = tf.Variable(tf.random_uniform((10,20)), name="w")
z = x @ w	# z = tf.matmul(x,w)
print(z)