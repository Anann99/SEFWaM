# SEFWaM-Deep-Learning-based-Smart-Ensembled-Framework-for-Waste-Management-
Research Paper on devising an ensemble network (CNN + XGBoost) having the best evaluation metrics, tested on Trashnet2.0.

Trashnet2.0 is a modification of Trashnet where instances have been re assigned classes as some instances were earlier wrongly classififed.

[[https://drive.google.com/u/0/uc?id=1gJPEeiseyBq3_Z1B0GhyZrxCtFKzrV-K](https://drive.google.com/drive/folders/1_2xJak4OnDiYYM8Dy2s3hCs4XnEnJJtT?usp=sharing)] is the link to download the zip file of Trashnet2.0.


Abstract - Waste generation has increased tremendously in the last decade. Efficient and Sustainable waste management is the need of the hour. With the massive land fillings covered under heaps of garbage, the segregation of waste in recyclable and non-recyclable will solve many problems around the globe. The necessity to classify the garbage into various classes such as paper, plastic and metal is rising, as different classes require different methods of disposing the garbage and some can even be recycled. 
The problem of automatic detection and segregation of the garbage can be broken down into two parts- first being automatic garbage classification which can be achieved using computer vision. Computer vision is performed on the trashnet dataset using the deep CNN model such as a Pre-trained Inception Resnet V2 which carries the further advantage of transferred learning, and it is ensembled with XGBoost to give better results. 
The paper throws light on the methodology opted for data preprocessing to expand the dataset using data augmentation, and other regularisation methods namely dropout, batch normalisation and early stopping to reduce overfitting and optimise the training process.

This repo contains the Data Preprocessing file of the dataset and the ensembed network of CNN-XGBoost file, both being run on google colab.
