# Mission 2: What Makes Deep Learning Different?

## 1. Introduction

Artificial Intelligence, Machine Learning and Deep Learning are related concepts, but they have different meanings. Understanding their differences helps engineers select suitable methods for solving problems.

## 2. Relationship Between AI, ML and DL

```text
Artificial Intelligence (AI)
             |
             v
      Machine Learning (ML)
             |
             v
        Deep Learning (DL)
```

**Artificial Intelligence (AI):** The broad field of creating systems that perform tasks requiring intelligence.

**Machine Learning (ML):** A branch of AI in which systems learn patterns from data.

**Deep Learning (DL):** A branch of ML that uses neural networks with multiple layers to learn complex patterns.

## 3. Comparison of Approaches

| Feature | Rule-Based System | Traditional ML | Deep Learning |
|---|---|---|---|
| Method | Follows predefined rules | Learns from data | Learns through multilayer neural networks |
| Feature selection | Rules are manually defined | Often requires feature engineering | Can learn features automatically |
| Typical data | Clearly defined conditions | Often structured data | Complex data, including images |
| Computing requirements | Usually low | Depends on the algorithm | Can be high |
| Example | Temperature alarm | Equipment failure prediction | Wafer defect image classification |

## 4. Rule-Based Systems

Rule-based systems follow instructions written by a programmer.

For example, a temperature monitoring system may activate an alarm when the temperature exceeds a predefined threshold.

**Advantages:**
- Easy to understand.
- Simple to implement for clearly defined conditions.
- Often requires limited computing resources.

**Limitations:**
- Rules must be written or updated manually.
- Complex patterns can be difficult to describe with fixed rules.

## 5. Traditional Machine Learning

Traditional machine learning algorithms learn relationships from examples. Engineers often select useful input features.

For example, a model can use temperature, vibration and current measurements to predict possible equipment failure.

It can work well with structured datasets and may be easier to interpret than some large neural networks.

## 6. Deep Learning

Deep learning uses neural networks with multiple layers to learn representations from data.

For example, a model trained on images may learn patterns that distinguish different defect categories.

**Advantages:**
- Can learn complex patterns.
- Can process images, audio and text.
- Can learn useful features automatically.

**Limitations:**
- May require large amounts of representative data.
- Can require significant computing resources.
- Can be difficult to interpret.
- May perform poorly on unfamiliar data.

## 7. Choosing the Right Approach

A rule-based system may be sufficient for simple threshold checks. Traditional machine learning may suit structured sensor data. Deep learning may be useful when the problem involves complicated patterns in images or other complex inputs.

A more complex model is not automatically better. The choice should depend on performance, data availability, cost and reliability requirements.

## Conclusion

AI is the broad field, ML learns patterns from data, and DL uses multilayer neural networks. Each approach has strengths and limitations, so engineers should choose the method that best suits the problem.

## Sources

1. Google for Developers — [Machine Learning Crash Course](https://developers.google.com/machine-learning/crash-course/)
2. Google for Developers — [Neural Networks](https://developers.google.com/machine-learning/crash-course/neural-networks)
3. Google for Developers — [Machine Learning](https://developers.google.com/machine-learning/)
