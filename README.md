# ai learning roadmap
Currently transitioning in to AI Engineering. This GitHub now reflects my journey from full-stack to applied AI. Scroll down to see the evolution.

# Day 1

Date: May 21st, 2025  
Topic: What is a Neural Network?,   
Video Resource: [What is a Neural Network?](https://www.youtube.com/watch?v=aircAruvnKk)

Today marks the beginning of my AI journey. I watched an intuitive explanation of neural networks by 3Blue1Brown and here’s what I learned:


# What is a Neural Network?

A neural network is a system inspired by the human brain that recognizes patterns in data. It processes inputs through layers of neurons to produce outputs such as identifying handwritten digits.


# Example Used: The Number "3"

The video used a 28x28 pixel image of the digit "3" (total 784 pixels). Each pixel acts as a neuron in the input layer and holds a value between:
- '0' (black/dark)
- '1' (white/bright)


# Network Architecture

1. Input Layer(1): 784 neurons (for each image pixel)
2. Hidden Layers(2&3):  
   - Layer 1: Detects basic shapes or features (e.g., strokes, loops)  
   - Layer 2: Combines those features into more complex shapes
3. Output Layer(4): 10 neurons representing digits '0–9'  
   - Outputs a probability score for each digit  
   - The highest score determines the predicted number


# Key Concepts

- Neuron: A unit that holds a number between 0 and 1  
- Weights: Determines the importance of each input  
- Bias: Adjusts the weighted sum before activation  
- Activation Functions:
  - Sigmoid: Smooth curve from 0 to 1  
  - ReLU: 'max(0, a)' only outputs positives  


# Insights

- Neural networks can break down images into features and edges.
- The model learns by adjusting weights and biases.
- For example, a "9" could be seen as a loop + vertical stroke. Recognizing these parts happens in the hidden layers.




