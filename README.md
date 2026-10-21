# IS-Back-Propagation

C# implementation of neural network back-propagation (4-5-3 network, tanh hidden layer,
softmax output), based on the article "Coding Neural Network Back-Propagation Using C#".

Course: CS345 - Renz Gabriel Etcuban

## Versions

| Folder | Description |
|--------|-------------|
| `Original/` | Baseline code as provided: mean squared error (MSE), no weight decay |
| `CrossEntropy/` | Cross-entropy error instead of MSE (output signal becomes `target - output`) |
| `WeightDecay/` | Cross-entropy + weight decay (L2 regularization, `weightDecay` = lambda) |

## Run

Each folder is its own project:

```
dotnet run --project Original
dotnet run --project CrossEntropy
dotnet run --project WeightDecay
```

## Results

Parameters: maxEpochs = 1000, learnRate = 0.05, momentum = 0.01, seed = 1

| Version | Train accuracy | Test accuracy |
|---------|----------------|---------------|
| Original (MSE) | 98.88% | 98.50% |
| CrossEntropy | TBD | TBD |
| WeightDecay (lambda = 0.001) | TBD | TBD |
