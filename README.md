Our solution to the [Humbpack Whale Identification Challenge](https://www.kaggle.com/c/whale-categorization-playground).
This project was done as a contribution for the [Neural Information Processing Conference 2018](https://www.ni.tu-berlin.de/menue/teaching_activities/all_courses/neural_information_processing_project/) of TU-Berlin.
The challenge was completed within the top 8% of participants.

https://www.kaggle.com/marschi

Abstract from documentation paper:

In this paper, we present our insights and solution to the Kaggle Humpback Whale Identification challenge, where individual whales must be identified by a picture of their fluke.
The data set is the Happy Whale’s database of over 25,000 images, gathered from research institutions and public contributors. Since this data set has only a couple of images per class (per whale), the task at hand falls into the category of Few-Shot Learning problems.
The performances of two different Machine Learning algorithms have been compared: a regular Convolutional Neural Network and a so called Siamese Network Architecture, which is a CNN variant tailored to Few-Shot Learning tasks.
In order to improve model performance, the images have been preprocessed by automatically cropping the areas of interest. 
Ultimately we found that the CNN slightly outperformed the Siamese Network, however we see more potential in the latter approach.
