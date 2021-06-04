# Tensorflow Weight Initialization and Training
The purpose of this repo was to understand a few things about tensorflow 2, trying out a few concepts as below:
- tensorflow datasets and how to install
- custom training loop, with sparse labels
- weights and bias init methods for Tensorflow

## Findings
- tensorflow 2 has various methods of intialization, the default is xavier uniform init
- bias will default to zeros
- you can change to various intialization methods via the kernel intialization argument, and can be manipulated via string

```python
tf.keras.layers.Dense(256, kernel_initializer='zeros', bias_initializer='ones')
```

- tensorflow datasets offers an easy to use way to load datasets

# TODO
- [x] trained cat dog classifier, testing out global average poolingin 2d (normal head seems to give better results)
- [x] Tested out various intialization methods, default seems to work best
- [ ] Test out with pytorch, maybe if time is available?
