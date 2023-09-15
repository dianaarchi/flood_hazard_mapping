# Towards urban flood hazard mapping using data-driven models


## Description:
We compared convolutional neural networks (CNNs) (image-based model) with traditional machine learning algorithms such as random forest (RF), support vector machine (SVM) and artificial neural networks (ANNs) to map urban flood susceptibility. We used a flood inventory and eleven predictive features representing topography, infrastructure and precipitation to develop the models. The results showed that the RF models outperformed other models and all the models performed well outside the training domain.

## Methodology
The main aim is to evaluate the models transferability to regions that were not included in the training data. We divided the dataset into training (60 %), validation (20 %) and testing (20 %) datasets. Firstly, we used the training and validation dataset to train the model and tune the hyper-parameters. Then, we used the testing dataset to evaluate the model performance among the training domain. Finally we used the reported flooded locations outside the training domain to evaluate the models' transferability in space.

## Models
We compared convolutional neural networks (CNNs) (image-based model) with traditional machine learning algorithms such as random forest (RF), support vector machine (SVM) and artificial neural networks (ANNs) to map urban flood susceptibility. We used the LeNet 5 architecture for the CNN 

![Figure 4](https://user-images.githubusercontent.com/57235564/209140709-1e221507-bf10-49fe-85ca-5ac47f224116.png)


## Results
The models performed well among and outside the training domain. 
