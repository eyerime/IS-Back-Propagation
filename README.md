# CodingBackProp

C# implementation of neural network back-propagation (4-5-3 network, tanh hidden layer,
softmax output, mean squared error), based on the article
"Coding Neural Network Back-Propagation Using C#".

Course: CS345 - Renz Gabriel Etcuban

## Run

```
dotnet run
```

## Version history

- **Original** - baseline code as provided (MSE error, no weight decay).
- *(upcoming)* Cross-entropy error and/or weight decay.

## Results

| Version | Train accuracy | Test accuracy |
|---------|----------------|---------------|
| Original (MSE) | 98.88% | 98.50% |

Parameters: maxEpochs = 1000, learnRate = 0.05, momentum = 0.01, seed = 1
