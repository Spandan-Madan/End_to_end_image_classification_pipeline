# End to end image classification pipeline

Most onlin tutorials present image classification as a problem of training a neural network. And there's at least a 100 tutorials on how to do that. If that is what you need, I recommend looking at [this tutorial](https://github.com/Spandan-Madan/Pytorch_fine_tuning_Tutorial) of mine on fine tuning.

But, there are many other steps that you need to understand and get right if you want to be sure you're doing something right. Otherwise, chances are high you'll fall prey to one of the biggest problems in Machine Learning - "Garbage In, Garbage Out".

Some of the things this tutorial will teach you include - 

- [] Preparing your data the right way. Data augmentation using transforms, loading and making sure you exactly know what you're feeding in to your network to learn. Remember, if your input doesn't look meaningful, the network really can't learn anything meaningful!
- [] Visualizing your results
- [] Evaluating your results. Classification accuracy is a single number which tells you hardly anything about how your network is working. In order to improve your network's performance it is important you understand how it works, when it fails, what it overfits to, what it fails to learn. And so on and so forth.
