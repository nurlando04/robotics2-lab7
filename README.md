# robotics2-lab7

### For this task I added two hidden layers decreasing the number of units by two at each layer. The higher number of units did not significantly improved the accuracy. 
### leakyReluLayer was found to be an optimal activation layer
```
    fullyConnectedLayer(512)
    leakyReluLayer
    fullyConnectedLayer(256)
    leakyReluLayer
    fullyConnectedLayer(128)
    leakyReluLayer
    fullyConnectedLayer(numClasses)  
    regressionLayer
```
### Number of epochs was increased to 20
### Batch size was set to 160
### Final error: 0.02677
