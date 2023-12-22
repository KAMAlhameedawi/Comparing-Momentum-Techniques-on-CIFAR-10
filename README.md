# Comparing-Momentum-Techniques-on-CIFAR-10
This code aims to comprehend and evaluate the performance of three distinct momentum optimization methods on the CIFAR-10 dataset: Adam, RMSprop, and Stochastic Gradient Descent (SGD). The following tasks are included in the code:
## Tasks:
## Preprocessing and Data Loading:

## Load the dataset for CIFAR-10.
Preprocess the information, making sure to normalize it.
![image](https://github.com/KAMAlhameedawi/Comparing-Momentum-Techniques-on-CIFAR-10/assets/149914341/b10bf1f4-fda3-4787-85b6-b2815948e54f)


## Architecture Model:

Convolutional neural networks (CNNs) should be designed in order to classify CIFAR-10 images.
To ensure fairness, make sure the architecture is the same for each experiment.
Baseline Study (SGD):

Stochastic Gradient Descent (SGD) is used as the optimizer to train the model.
Keep track of important metrics like training time, loss, and accuracy for both training and validation.
Visualize the training process.

## Adam's Trial:

Utilizing the Adam optimizer, train the identical model.
Compare the SGD experiment's performance metrics with it.
Examine any variations in the rate of convergence or the accuracy at the end.
## RMSprop Test:

Utilizing the RMSprop optimizer, train the identical model.
Evaluate the performance metrics in relation to the SGD and Adam studies.
Examine any variations in the rate of convergence or the accuracy at the end.

## Comparative Evaluation:

To compare the training progress of the three optimization techniques, create visualizations (tables or graphs).
Talk about each optimizer's advantages and disadvantages in light of the experimental findings.
Take into account factors like final accuracy, stability, and convergence speed.

## Talk:

Consider the variations and parallels between the optimizers that you have seen.
Talk about the effects of each optimizer's hyperparameters (learning rate, momentum, etc.) on performance.
Provide advice on which optimizer to use depending on the properties of the dataset.

## In summary:

Write a summary of the main conclusions and findings from the experiments.
Talk about the real-world effects of selecting a particular optimizer for neural network training.
Loading Execution Data:

The datasets.cifar10.load_data() function is used to load the CIFAR-10 dataset.
## Architecture Model:


Convolutional layers, max pooling, flattening, and dense layers are the components of a CNN model.
Trials:

Three experiments are carried out by the code with various optimizers (SGD, Adam, RMSprop).
Accuracy and training progress are tracked and compared between experiments.

## Illustrations:

Visualizations comparing the training accuracy of various optimizers are made with Matplotlib.
Talk and Wrap-Up:

There are sections in the code for talking about the observations, results, and wrapping up the experiments.

![image](https://github.com/KAMAlhameedawi/Comparing-Momentum-Techniques-on-CIFAR-10/assets/149914341/49c434fc-af1c-4fed-b1f5-9d9d12a75ba1)
