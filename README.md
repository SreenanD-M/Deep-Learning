# Deep-Learning
Deep Learning is a subset of machine learning that uses artificial neural networks to model and solve complex problems. It excels in areas like image recognition, natural language processing, and predictive analytics by automatically learning features from raw data.

## Key Skills & Tools

**Frameworks:** TensorFlow, PyTorch, Keras

**Techniques:** CNNs, RNNs, LSTMs, Transformers

**Applications:** Image classification, sentiment analysis, time series forecasting, anomaly detection

**Languages:** Python, SQL

## Python code example :
import tensorflow as tf
model = tf.keras.Sequential([tf.keras.layers.Dense(1, input_shape=[1])])
model.compile(optimizer='sgd', loss='mean_squared_error')
model.fit([1,2,3,4], [2,4,6,8], epochs=10)

