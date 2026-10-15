# micrograd — learning notes

My walkthrough of Andrej Karpathy's [micrograd](https://github.com/karpathy/micrograd) and the video
["The spelled-out intro to neural networks and backpropagation"](https://www.youtube.com/watch?v=VMj-3S1tku0).

## Structure

- `notebooks/` — Jupyter notebooks I write while following the lecture
- `micrograd/engine.py` — the `Value` class (scalar autograd)
- `micrograd/nn.py` — `Neuron`, `Layer`, `MLP` built on top of `Value`

## Progress

- [ ] Derivatives intuition (numerical slope)
- [ ] `Value` class: `+`, `*`, graph visualization
- [ ] Manual backprop through an expression
- [ ] Automatic `backward()` with topological sort
- [ ] More ops: `tanh`, `exp`, `pow`, `-`, `/`
- [ ] Compare against PyTorch
- [ ] `Neuron`, `Layer`, `MLP`
- [ ] Training loop (loss, gradient descent, `zero_grad`)
