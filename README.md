# Micrograd Engine

A scalar-valued autograd engine for deep learning.

## Features
- Automatic differentiation
- Computational graph
- Backpropagation
- Optimisation

## Example
```python
from micrograd import Value
x = Value(2.0)
y = x * 3 + 1
y.backward()
print(x.grad)  # 3.0
```
