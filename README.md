# Neurotic

A tiny neural network you can watch learn to tell cats from dogs. It's an interactive companion for learning how neural networks work, from the perceptron to backpropagation.

**Try it:** https://gabeska.github.io/neurotic/

Everything lives in a single `index.html` with no dependencies or build step. Open it in any browser and it works offline.

## The ten labs

1. **Perceptron & XOR**: a classic perceptron learns AND, OR and NAND but never XOR. A hidden layer fixes it, shown both hand-built and learned by backprop, with a "hidden space" view of why it works.
2. **Two features**: cats and dogs as points (ear pointiness, snout length). See the decision boundary, each hidden neuron's line, and the full math for any example.
3. **Gradient descent**: a two-parameter model whose whole loss landscape you can see. Try learning rate, mini-batch vs. stochastic gradients, and momentum.
4. **Backpropagation**: step through one forward and backward pass of a 2→2→1 network with every number shown, and check each gradient against a brute-force nudge.
5. **Pictures**: a network learns from 20×20 cat and dog faces. See what each hidden neuron looks for, and draw your own animals to test it.
6. **Perceptron → LLM**: seven steps from the 1958 perceptron to large language models (multi-layer networks, convolutional nets, recurrent nets, word embeddings, attention and the Transformer). Each step has a diagram, what it fixed, and the weakness that led to the next one. A log-scale chart compares weight counts, from 3 to 175 billion.
7. **How an LLM writes**: train a tiny neural language model on cat and dog sentences in your browser, then generate text one word at a time. See the next-word probabilities, change the temperature, top-k and context window, pick words yourself, and watch the word embeddings arrange themselves.
8. **Prompt → reply**: a tiny chat model, trained in your browser on short conversations, shows that a prompt and its reply are one piece of text the model continues token by token. Change the prompt and watch the reply change, see which prompt words each reply word depended on, and turn off the chat template or the end token to see what they do.
9. **Tokens**: a byte-pair-encoding tokenizer trained on this website's own text. Watch it learn merges one at a time, type any text to see its tokens and ids, and see why "strawberry" is hard for an LLM to spell and why emoji and other languages cost more tokens.
10. **Attention, learned**: one attention head learns from scratch, in your browser, to answer "which animal / colour / food?" about a sentence. Watch its attention snap onto the right word, compare all three questions at once, and read the query·key scores behind it.
