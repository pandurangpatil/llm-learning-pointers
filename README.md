# llm-learning-pointers #

## Best playlist by Andrej Karpathy
He will walk you through the small neural network crafted step by step, explaining every minute detail. 
Then goes on to build GPT2 LLM incrementally.

https://www.youtube.com/playlist?list=PLAqhIrjkxbuWI23v9cThsA9GvCAUhRvKZ

### LLM - Short introduction to embedding

The following are a few resources to understand embedding vectors.
1. This one gives some basic visualization - https://www.youtube.com/watch?v=hVM8qGRTaOA
2. This one enhances this understanding - https://youtu.be/wjZofJX0v4M?si=5k1sxRuTwCdxzA20


### LLM - Query, Key and Value ( Selft Attention, Multi-Head Attention & Cross attention)

1. https://youtu.be/eMlx5fFNoYc?si=Vl_oFn1UUygh_8Lk
2. https://www.youtube.com/watch?v=KMHkbXzHn7s

### 1. The spelled-out intro to neural networks and backpropagation: building micrograd
https://www.youtube.com/watch?v=VMj-3S1tku0&list=PLAqhIrjkxbuWI23v9cThsA9GvCAUhRvKZ&index=2

Explains how the gradient calculation is being done, single perceptron, multi-layer perceptron ( small neural network ). Covers gradient calculation, loss, updating the weights. 

<details>
<summary> Click to expand chapters</summary>

<br/>

- [00:00:00 — Intro](https://www.youtube.com/watch?v=VMj-3S1tku0&t=0s)
- [00:00:25 — Micrograd overview](https://www.youtube.com/watch?v=VMj-3S1tku0&t=25s)
- [00:08:08 — Derivative of a simple function with one input](https://www.youtube.com/watch?v=VMj-3S1tku0&t=488s)
- [00:14:12 — Derivative of a function with multiple inputs](https://www.youtube.com/watch?v=VMj-3S1tku0&t=852s)
- [00:19:09 — Starting the core Value object of micrograd and its visualization](https://www.youtube.com/watch?v=VMj-3S1tku0&t=1149s)
- [00:32:10 — Manual backpropagation example #1: simple expression](https://www.youtube.com/watch?v=VMj-3S1tku0&t=1930s)
- [00:51:10 — Preview of a single optimization step](https://www.youtube.com/watch?v=VMj-3S1tku0&t=3070s)
- [00:52:52 — Manual backpropagation example #2: a neuron](https://www.youtube.com/watch?v=VMj-3S1tku0&t=3172s)
- [01:09:02 — Implementing the backward function for each operation](https://www.youtube.com/watch?v=VMj-3S1tku0&t=4142s)
- [01:17:32 — Implementing the backward function for a whole expression graph](https://www.youtube.com/watch?v=VMj-3S1tku0&t=4652s)
- [01:22:28 — Fixing a backprop bug when one node is used multiple times](https://www.youtube.com/watch?v=VMj-3S1tku0&t=4948s)
- [01:27:05 — Breaking up a tanh, exercising with more operations](https://www.youtube.com/watch?v=VMj-3S1tku0&t=5225s)
- [01:39:31 — Doing the same thing but in PyTorch: comparison](https://www.youtube.com/watch?v=VMj-3S1tku0&t=5971s)
- [01:43:55 — Building out a neural net library (multi-layer perceptron) in micrograd](https://www.youtube.com/watch?v=VMj-3S1tku0&t=6235s)
- [01:51:04 — Creating a tiny dataset, writing the loss function](https://www.youtube.com/watch?v=VMj-3S1tku0&t=6664s)
- [01:57:56 — Collecting all of the parameters of the neural net](https://www.youtube.com/watch?v=VMj-3S1tku0&t=7076s)
- [02:01:12 — Doing gradient descent optimization manually, training the network](https://www.youtube.com/watch?v=VMj-3S1tku0&t=7272s)
- [02:14:03 — Summary of what we learned, how to go towards modern neural nets](https://www.youtube.com/watch?v=VMj-3S1tku0&t=8043s)
- [02:16:46 — Walkthrough of the full code of micrograd on GitHub](https://www.youtube.com/watch?v=VMj-3S1tku0&t=8206s)
- [02:21:10 — Real stuff: diving into PyTorch, finding their backward pass for tanh](https://www.youtube.com/watch?v=VMj-3S1tku0&t=8470s)
- [02:24:39 — Conclusion](https://www.youtube.com/watch?v=VMj-3S1tku0&t=8679s)
- [02:25:20 — Outtakes :)](https://www.youtube.com/watch?v=VMj-3S1tku0&t=8720s)

</details>

## Internet learning resources for Neural networks
1. Simple perceptron ( machine neuron ) training example - https://youtu.be/l-9ALe3U-Fg?si=m2Hg2JliM48oKKF6
2. ⁠Then go through this list of videos by this professor. This one is covering concepts in sequence - https://www.youtube.com/playlist?list=PL2zRqk16wsdo3VJmrusPU6xXHk37RuKzi
3. Smaller version of trained Neural Network flow - https://www.youtube.com/watch?v=ILsA4nyG7I0&list=PLVZqlMpoM6kaJX_2lLKjEhWI0NlqHfqzp&index=1&t=596s
4. Then go through this Video, which explains the kernel in CNN - https://www.youtube.com/watch?v=8rrHTtUzyZA&list=PLZHQObOWTQDMp_VZelDYjka8tnXNpXhzJ&index=1

## Maths learning resources to understand maths used in Neural Networks

1. Calculus https://brilliant.org/courses/calculus-nutshell/
2. Vectors (Tensors are an extension of vectors) - https://brilliant.org/courses/vectors/
3. Tensor - https://www.youtube.com/watch?v=k2FP-T6S1x0
4. Essense of Calculus - https://www.youtube.com/playlist?list=PLZHQObOWTQDMsr9K-rj53DwVRMYO3t5Yr
5. Essense of Linear Algebra - https://www.youtube.com/playlist?list=PLZHQObOWTQDPD3MizzM2xVFitgF8hE_ab

## Bridge between Maths and Neural Networks
1. Linear Algebra for Machine Learning and Data Science - https://www.youtube.com/watch?v=Wi5hWa_XEck
2. Probability & Statistics for Machine Learning and Data Science - https://www.youtube.com/watch?v=DCZSkoVvkQI
3. Differential Equations - https://www.youtube.com/playlist?list=PLZHQObOWTQDNPOjrT6KVlfJuKtYTftqH6
4. A video about neural networks, function approximation, machine learning, and mathematical building blocks - https://www.youtube.com/watch?v=TkwXa7Cvfr8

## Coding

1. Comprehensive Pytorch - https://www.youtube.com/playlist?list=PLZbbT5o_s2xrfNyHZsM6ufI0iZENK9xgG
