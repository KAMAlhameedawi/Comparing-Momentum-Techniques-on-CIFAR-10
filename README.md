# Comparing-Momentum-Techniques-on-CIFAR-10
This code aims to comprehend and evaluate the performance of three distinct momentum optimization methods on the CIFAR-10 dataset: Adam, RMSprop, and Stochastic Gradient Descent (SGD). The following tasks are included in the code:
## Tasks:
## Preprocessing and Data Loading:

## Load the dataset for CIFAR-10.
Preprocess the information, making sure to normalize it.
Here are the classes in the dataset, as well as 10 random images from each:
airplane										
automobile										
bird										
cat										
deer										
dog										
frog										
horse										
ship										
truck	
![image](https://github.com/KAMAlhameedawi/Comparing-Momentum-Techniques-on-CIFAR-10/assets/149914341/0172881d-d5d6-47fe-a3fa-f21f4ff6ede8)



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

## Result


Epoch 1/10


1563/1563 [==============================] - 62s 38ms/step - loss: 1.9435 - accuracy: 0.2999 - val_loss: 1.6813 - val_accuracy: 0.4056
Epoch 2/10
1563/1563 [==============================] - 58s 37ms/step - loss: 1.5497 - accuracy: 0.4464 - val_loss: 1.4328 - val_accuracy: 0.4817
Epoch 3/10
1563/1563 [==============================] - 57s 36ms/step - loss: 1.3803 - accuracy: 0.5097 - val_loss: 1.3733 - val_accuracy: 0.5157
Epoch 4/10
1563/1563 [==============================] - 80s 51ms/step - loss: 1.2757 - accuracy: 0.5518 - val_loss: 1.2141 - val_accuracy: 0.5721
Epoch 5/10
1563/1563 [==============================] - 123s 78ms/step - loss: 1.1937 - accuracy: 0.5803 - val_loss: 1.2164 - val_accuracy: 0.5705
Epoch 6/10
1563/1563 [==============================] - 128s 82ms/step - loss: 1.1291 - accuracy: 0.6042 - val_loss: 1.1310 - val_accuracy: 0.6020
Epoch 7/10
1563/1563 [==============================] - 129s 83ms/step - loss: 1.0737 - accuracy: 0.6239 - val_loss: 1.1510 - val_accuracy: 0.5945
Epoch 8/10
1563/1563 [==============================] - 139s 89ms/step - loss: 1.0245 - accuracy: 0.6429 - val_loss: 1.0557 - val_accuracy: 0.6374
Epoch 9/10
1563/1563 [==============================] - 108s 69ms/step - loss: 0.9819 - accuracy: 0.6605 - val_loss: 1.0818 - val_accuracy: 0.6258
Epoch 10/10
1563/1563 [==============================] - 123s 78ms/step - loss: 0.9436 - accuracy: 0.6717 - val_loss: 1.0663 - val_accuracy: 0.6249
Epoch 1/10
1563/1563 [==============================] - 139s 84ms/step - loss: 1.4697 - accuracy: 0.4728 - val_loss: 1.2052 - val_accuracy: 0.5776
Epoch 2/10
1563/1563 [==============================] - 126s 80ms/step - loss: 1.1249 - accuracy: 0.6054 - val_loss: 1.0574 - val_accuracy: 0.6319
Epoch 3/10
1563/1563 [==============================] - 129s 83ms/step - loss: 0.9999 - accuracy: 0.6517 - val_loss: 1.0056 - val_accuracy: 0.6494
Epoch 4/10
1563/1563 [==============================] - 106s 68ms/step - loss: 0.9161 - accuracy: 0.6813 - val_loss: 0.9554 - val_accuracy: 0.6611
Epoch 5/10
1563/1563 [==============================] - 123s 79ms/step - loss: 0.8522 - accuracy: 0.7039 - val_loss: 0.8999 - val_accuracy: 0.6916
Epoch 6/10
1563/1563 [==============================] - 136s 87ms/step - loss: 0.8006 - accuracy: 0.7215 - val_loss: 0.8895 - val_accuracy: 0.6962
Epoch 7/10
1563/1563 [==============================] - 139s 89ms/step - loss: 0.7561 - accuracy: 0.7370 - val_loss: 0.9399 - val_accuracy: 0.6842
Epoch 8/10
1563/1563 [==============================] - 150s 96ms/step - loss: 0.7138 - accuracy: 0.7523 - val_loss: 0.9352 - val_accuracy: 0.6877
Epoch 9/10
1563/1563 [==============================] - 209s 134ms/step - loss: 0.6733 - accuracy: 0.7634 - val_loss: 0.9154 - val_accuracy: 0.6969
Epoch 10/10
1563/1563 [==============================] - 171s 110ms/step - loss: 0.6419 - accuracy: 0.7764 - val_loss: 0.9023 - val_accuracy: 0.7086
Epoch 1/10
1563/1563 [==============================] - 343s 212ms/step - loss: 1.4787 - accuracy: 0.4704 - val_loss: 1.2360 - val_accuracy: 0.5628
Epoch 2/10
1563/1563 [==============================] - 166s 106ms/step - loss: 1.0904 - accuracy: 0.6223 - val_loss: 1.1242 - val_accuracy: 0.6194
Epoch 3/10
1563/1563 [==============================] - 124s 80ms/step - loss: 0.7299 - accuracy: 0.7489 - val_loss: 0.9838 - val_accuracy: 0.6747
Epoch 7/10
1563/1563 [==============================] - 117s 75ms/step - loss: 0.6674 - accuracy: 0.7689 - val_loss: 0.9064 - val_accuracy: 0.7067
Epoch 8/10
1563/1563 [==============================] - 117s 75ms/step - loss: 0.6180 - accuracy: 0.7864 - val_loss: 0.9761 - val_accuracy: 0.6937
Epoch 9/10
1563/1563 [==============================] - 189s 121ms/step - loss: 0.5191 - accuracy: 0.8224 - val_loss: 1.0454 - val_accuracy: 0.7020

![image](https://github.com/KAMAlhameedawi/Comparing-Momentum-Techniques-on-CIFAR-10/assets/149914341/49c434fc-af1c-4fed-b1f5-9d9d12a75ba1)
