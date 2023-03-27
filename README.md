# Hypothesis

 Given an image dataset of infected and uninfected cells, can we predict which cells have been parasitized by malaria with at least a 75% accuracy rate.

# Research Question

Can we use image data to predict which cells contain malaria?

## SRC Section

### Installing/Building the Code

To run the .pynb file, he following packages must be installed and loaded: mnist, Sequential, Conv2D, MaxPool2D, Flatten, Dropout, and Dense

### Usage of Code

## Data Section

### Link to Data

https://www.kaggle.com/datasets/iarunava/cell-images-for-detecting-malaria

### Data Dictionary

| Variable | Definition | 
| ------- | --- |
| Parasitized | Images of red blood cells that have been infected by mosquitoes.|
| Uninfected | Images of red blood cells that have not been infected by mosquitoes. |

### Notes about use of Data

## Figures Section
### Table of Contents
| Figure | Key Takeaways | 
| ------- | --- |
| trainingandvalidationaccuracy.png | Plot shows both the training and validation accuracies for classifying a cell as parsitized (malaria) or uninfected. We have around 93% accuracy rate.|
| trainingandvalidationloss.png |  Plot shows both the training and validation losses for classifying a cell as parsitized (malaria) or uninfected. Loss is under 0.3 which is good, however there may be some overfitting with the training data.|

## References Section

### References

A. Rosebrock, “Deep learning and medical image analysis with Keras,” PyImageSearch, 29-Dec-2022. [Online]. Available: https://pyimagesearch.com/2018/12/03/deep-learning-and-medical-image-analysis-with-keras/. [Accessed: 17-Mar-2023]. 
Arunava, “Malaria Cell Images Dataset,” Kaggle, 05-Dec-2018. [Online]. Available: https://www.kaggle.com/datasets/iarunava/cell-images-for-detecting-malaria. [Accessed: 16-Mar-2023]. 
 “CDC - Malaria - about malaria - faqs,” Centers for Disease Control and Prevention, 22-Mar-2022. [Online]. Available: https://www.cdc.gov/malaria/about/faqs.html. [Accessed: 16-Mar-2023]. 
“CDC - Malaria - malaria worldwide - impact of malaria,” Centers for Disease Control and Prevention, 16-Dec-2021. [Online]. Available: https://www.cdc.gov/malaria/malaria_worldwide/impact.html. [Accessed: 16-Mar-2023]. 
“Malaria in Africa,” UNICEF DATA, 09-Mar-2023. [Online]. Available: https://data.unicef.org/topic/child-health/malaria/#:~:text=Nearly%20every%20minute%2C%20a%20child%20under%20five%20dies%20of%20malaria,under%205%20years%20of%20age. [Accessed: 16-Mar-2023]. 
Y. Gavrilova, “What are convolutional neural networks?,” Serokell Software Development Company, 03-Aug-2021. [Online]. Available: https://serokell.io/blog/introduction-to-convolutional-neural-networks. [Accessed: 16-Mar-2023].


### Acknowledgements

Special thanks to Professor Loreto Alonzi and Daiqing Qi for their guidance.

### Links to M1 and M2 Assignments

[M1 assignment](https://docs.google.com/document/d/1QOKsJRAqTqHLMnBxCpUXNcdGi2G9eZs9G3AI4apKRPU/edit?usp=sharing)

[M2 assignment](https://docs.google.com/document/d/1t4ODOfT9-8qYV1OFwtb8IgzkjOh5x6ejc2H_a3F6Tow/edit?usp=sharing)




