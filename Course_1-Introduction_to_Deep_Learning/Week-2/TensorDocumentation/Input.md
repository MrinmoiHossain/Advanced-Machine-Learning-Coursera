### Placeholder
```
import tensorflow as tf

x = tf.placeholder(tf.float32, (None, 10))
```

### Variable
```
import tensorflow as tf

w = tf.get_variable("w", shape=(10,20), dtype=tf.float32)
w = tf.Variable(tf.random_uniform((10,20)), name="w")
```

### Constant
```
import tensorflow as tf

c = tf.constant(np.ones((4,4)))
```