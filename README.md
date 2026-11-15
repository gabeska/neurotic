# Neurotic

A tiny neural network you can watch learn to tell cats from dogs. It's an interactive companion for learning how neural networks work, from the perceptron to backpropagation.

**Try it:** https://gabeska.github.io/neurotic/

Everything lives in a single `index.html` with no dependencies or build step. Open it in any browser and it works offline.

## The five labs

1. **Perceptron & XOR**: a classic perceptron learns AND, OR and NAND but never XOR. A hidden layer fixes it, shown both hand-built and learned by backprop, with a "hidden space" view of why it works.
2. **Two features**: cats and dogs as points (ear pointiness, snout length). See the decision boundary, each hidden neuron's line, and the full math for any example.
3. **Gradient descent**: a two-parameter model whose whole loss landscape you can see. Try learning rate, mini-batch vs. stochastic gradients, and momentum.
4. **Backpropagation**: step through one forward and backward pass of a 2→2→1 network with every number shown, and check each gradient against a brute-force nudge.
5. **Pictures**: a network learns from 20×20 cat and dog faces. See what each hidden neuron looks for, and draw your own animals to test it.
