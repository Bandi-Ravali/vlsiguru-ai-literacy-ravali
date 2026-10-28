# Mission 2: What Makes Deep Learning Different?

## Introduction

Artificial intelligence, machine learning and deep learning are related concepts, but they do not mean exactly the same thing. Understanding their differences helps engineers select an appropriate approach for a problem.

## Relationship Between AI, ML and DL

```text
Artificial Intelligence (AI)
          |
          v
   Machine Learning (ML)
          |
          v
     Deep Learning (DL)
```

Artificial intelligence is the broad field. Machine learning is a branch of AI, and deep learning is a branch of machine learning that uses neural networks with multiple layers.

## Comparison of Approaches

| Feature | Rule-Based System | Traditional Machine Learning | Deep Learning |
|---|---|---|---|
| Main method | Predefined rules | Learns patterns from data | Learns complex patterns through multilayer neural networks |
| Feature selection | Rules are manually defined | Features are often selected or engineered manually | Features can often be learned automatically |
| Data requirements | Depends on the rules and problem | Often works well with structured data | Frequently benefits from large datasets |
| Computing needs | Usually low | Depends on the algorithm | Can be high for large models |
| Example | Temperature alarm | Predicting equipment failure from sensor measurements | Recognizing defects in wafer images |

## How Deep Learning Works

Deep learning models process input data through multiple layers. Early layers may learn simple patterns, while later layers can combine them into more complex representations.

For example, in image recognition, a network may learn simple edges and shapes before learning more complex visual patterns. The exact representations depend on the model and training data.

## Advantages of Deep Learning

- Learns complex patterns from data.
- Can automatically learn useful representations from images, audio and text.
- Supports applications such as image classification, speech recognition and language processing.
- Can perform well when the training data represents the problem effectively.

## Limitations of Deep Learning

- May require large quantities of representative data.
- Can require significant computing resources.
- May be difficult to interpret.
- Can learn unwanted biases from its training data.
- Can perform poorly on data that differs significantly from its training examples.

## Choosing the Right Approach

A rule-based system may be suitable when the rules are simple and clearly defined. Traditional machine learning may work well for structured datasets with useful engineered features. Deep learning may be useful when the data contains complex patterns, such as images or audio.

More complex models are not automatically better. Model selection should consider accuracy, cost, data availability, interpretability and reliability.

## Conclusion

Deep learning is a powerful approach within machine learning, but the best solution depends on the problem and available data. Engineers should compare suitable methods rather than assuming that the most complex model is always the best.

## Sources

1. Google for Developers — [Machine Learning Crash Course](https://developers.google.com/machine-learning/crash-course/)
2. Google for Developers — [Neural Networks](https://developers.google.com/machine-learning/crash-course/neural-networks)
3. Google for Developers — [Machine Learning](https://developers.google.com/machine-learning/)
