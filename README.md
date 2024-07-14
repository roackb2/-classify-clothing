# Classify Clothing

An simple project by using the [Fashion MNIST](https://github.com/zalandoresearch/fashion-mnist) data set and neural networks to predict the category of the clothes.

## Architecture

A simple neural network with three leayers, each one of input size 28*28, 100 and 10. The first two using ReLU activation and the last one using linear activation, with `from_logits=True` while compiling.

## Evaluation

```python
{'accuracy': 0.8525999784469604, 'loss': 0.4540776014328003}
```

Need further improvements afterwards.