# Hypothesis

 Given an image dataset of infected and uninfected cells, can we predict which cells have been parasitized by malaria with at least a 75% accuracy rate.

# Research Question

Can we use image data to predict which cells contain malaria?

## SRC Section

### Installing/Building the Code

To run the .pynb file, the following packages must be installed and loaded: # numpy as np, pandas as pd, matplotlib.pyplot as plt, shutil, os,
from keras.preprocessing.image import ImageDataGenerator,from keras import layers, from keras import models, matplotlib.pyplot as plt, and matplotlib.image as mpimg.

Once all these packages are loaded make sure to set up directories for the copies of the data to go into-this can be done by simply running the ipynb file as well.

### Usage of Code
This code is intended for classifying cells as 'parasitized' (with malaria) or uninfected. It will split the images into training, validation, and test sets and then proceed to make use of the keras package to train the model. Using a convolutional neural network, the program should be able to classify images with about a 93% accuracy rate.

## Data Section

### Data Dictionary

| Variable | Definition | 
| ------- | --- |
| Parasitized | Images of red blood cells that have been infected by mosquitoes.|
| Uninfected | Images of red blood cells that have not been infected by mosquitoes. |

### Link to Data

https://www.kaggle.com/datasets/iarunava/cell-images-for-detecting-malaria


### Notes about use of Data
The data was originally from the NIH but was downloaded from kaggle. It is being used to classify cells as "parasitized" (with malaria) or "uninfected".

## Figures Section
### Table of Contents
| Figure | Key Takeaways | 
| ------- | --- |
| trainingandvalidationaccuracy.png | Plot shows both the training and validation accuracies for classifying a cell as parsitized (malaria) or uninfected. We have around 93% accuracy rate.|
| trainingandvalidationloss.png |  Plot shows both the training and validation losses for classifying a cell as parsitized (malaria) or uninfected. Loss is under 0.3 which is good, however there may be some overfitting with the training data.|

## References Section

### References

Anjanatiha, “Malaria detection using Keras (accuracy 95%),” Kaggle, 14-Mar-2019. [Online]. Available: https://www.kaggle.com/code/anjanatiha/malaria-detection-using-keras-accuracy-95#10.-Model-Performance. [Accessed: 27-Mar-2023]. 

A. Rosebrock, “Deep learning and medical image analysis with Keras,” PyImageSearch, 29-Dec-2022. [Online]. Available: https://pyimagesearch.com/2018/12/03/deep-learning-and-medical-image-analysis-with-keras/. [Accessed: 17-Mar-2023]. 

Arunava, “Malaria Cell Images Dataset,” Kaggle, 05-Dec-2018. [Online]. Available: https://www.kaggle.com/datasets/iarunava/cell-images-for-detecting-malaria. [Accessed: 16-Mar-2023]. 

A. Y. Xu, “Building a malaria classifier with Keras: Background &amp; Implementation,” Medium, 22-Mar-2019. [Online]. Available: https://medium.com/gradientcrescent/building-a-malaria-classifier-with-keras-background-implementation-d55c32773afa. [Accessed: 27-Mar-2023]. 

“CDC - Malaria - about malaria - faqs,” Centers for Disease Control and Prevention, 22-Mar-2022. [Online]. Available: https://www.cdc.gov/malaria/about/faqs.html. [Accessed: 16-Mar-2023]. 

“CDC - Malaria - malaria worldwide - impact of malaria,” Centers for Disease Control and Prevention, 16-Dec-2021. [Online]. Available: https://www.cdc.gov/malaria/malaria_worldwide/impact.html. [Accessed: 16-Mar-2023]. 

“Malaria in Africa,” UNICEF DATA, 09-Mar-2023. [Online]. Available: https://data.unicef.org/topic/child-health/malaria/#:~:text=Nearly%20every%20minute%2C%20a%20child%20under%20five%20dies%20of%20malaria,under%205%20years%20of%20age. [Accessed: 16-Mar-2023]. 

Y. Gavrilova, “What are convolutional neural networks?,” Serokell Software Development Company, 03-Aug-2021. [Online]. Available: https://serokell.io/blog/introduction-to-convolutional-neural-networks. [Accessed: 16-Mar-2023].


### Acknowledgements

Special thanks to Professor Loreto Alonzi and Daiqing Qi for their guidance. Thanks to Fadumo Hussein and Sam Richarson for their assistance.

### Links to M1 and M2 Assignments

[M1 assignment](https://docs.google.com/document/d/1QOKsJRAqTqHLMnBxCpUXNcdGi2G9eZs9G3AI4apKRPU/edit?usp=sharing)

[M2 assignment](https://docs.google.com/document/d/1t4ODOfT9-8qYV1OFwtb8IgzkjOh5x6ejc2H_a3F6Tow/edit?usp=sharing)




