---
title: "Neural Networks"
impact: MEDIUM
impactDescription: "Supporting concept that enhances domain understanding"
tags: networks, neural, technology
---

A neural network is a mathematical structure with layers of interconnected nodes. Each connection has a weight that gets adjusted during training to minimize prediction error.

**Types of Neural Networks**:

- **Artificial Neural Networks (ANN)**: Simplest form with input → hidden → output layers. Good for tabular data and predicting continuous values or categories.

- **Convolutional Neural Networks (CNNs)**: Specialized for images and spatial data. Use convolutional layers detecting local patterns (edges, textures) and build to complex features (faces, objects). Power computer vision: medical imaging, autonomous vehicle perception, quality control inspection.

- **Recurrent Neural Networks (RNNs)**: Handle sequential data where order matters: time series, text, audio. Have memory—previous inputs influence current predictions. LSTMs (Long Short-Term Memory networks) remember information over longer sequences. Used for stock price prediction, equipment failure forecasting, speech recognition.

- **Transformers**: Modern architecture revolutionizing NLP and beyond. Use attention mechanisms focusing on relevant parts of input. Process all elements simultaneously (unlike RNNs). Capture long-range dependencies and enable scalable training on massive datasets. Foundation for GPT, BERT, and large language models.

**Activation Functions** introduce non-linearity enabling networks to learn complex patterns:

- **ReLU (Rectified Linear Unit)**: Output = max(0, x). Most common; fast to compute, prevents vanishing gradients.
- **Sigmoid**: Output between 0 and 1; interpretable as probability but slows learning.
- **Tanh**: Output between -1 and 1; similar to sigmoid with slightly better properties.
- **Softmax**: Used in output layer for multi-class classification; outputs probability distribution.

**Training Process**:

1. Forward pass: Move data through network to produce predictions
2. Calculate loss: Measure how wrong predictions are
3. Backward pass (backpropagation): Compute how much each weight contributed to loss
4. Gradient descent: Iteratively adjust weights to minimize loss
