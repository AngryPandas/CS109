# CS109 - Final Project
#### * Project Name : Face Detection and Gender Classification
#### * Team Name : Angry Pandas
###### 1) Team member's github ids : xchang4, jeewon-hwang, zelong430, xdai1091
###### 2) Website : [http://cs109-angrypandas.weebly.com/](http://cs109-angrypandas.weebly.com/) 
###### 3) Sceencast : [https://youtu.be/8jJzDEq1tFA](https://youtu.be/8jJzDEq1tFA)
###### 4) Database we used : [Nottingham Face Detection Database](http://pics.psych.stir.ac.uk/2D_face_sets.htm)
###### 5) Non-standard Python libraries we used :
CV2, glob, PIL, sklearn, panda, matplotlib, seaborn
We used haarcascade_frontalface_default.xml to detect the face.






## Overview of our Project
##### Background and Motivation
Face recognition has become one of the most popular research areas, as faces’ expressions contain much information neuroscientists and psychologists are interested in. It is also one of the most successful applications of computer vision and machine learning researches. As such, the team is motivated to use what CS109 has taught, such as PCA, KNN, SVN, etc. in the class to implement a simple, yet practical, face detection and recognition project. The expected background researches for this project covers advanced classification algorithms and some tools to evaluate/estimate performance, such as Principal-Component-Analysis (PCA), K-Nearest-Neighbors (KNN) and Linear-Support-Vector-Machine (Linear SVM), Confusion Matrix and ROC curve.

##### Project Objectives
The goal of this project is to finish a classification algorithm to detect and distinguish objects(faces) in images. During the project, the team members will consolidate the knowledge given in classes and integrate them to deliver a completed, working, interesting project. The project itself is not a breakthrough technological achievement, yet it is an opportunity for team members to review, learn and think.

##### Feature:
1: Face detection: detect the face in a photo.

2: Face recognition/classification: classify the gender of the detected face.

##### Design Overview
1: Face detection: The OpenCV(Open Source Computer Vision) module would be used to detect the face.

2: Face recognition: PCA(Principal Component Analysis) would be used to reduce the dimension. KNN(K-Nearest-Neighbors), SVM(Support Vector Machines) and Logistic Regression would be used to do the gender classification.

3: Parameterization: k-fold cross-validation approach would be applied to avoid over-fitting scenario.

4:Model assessment: AUROC (area under ROC curve) will be used to evaluate the accuracy of results and the performance of algorithms.

##### Verification
Train/Test data: data will be divided into the train dataset and the test dataset. The train dataset would be used to develop the algorithm and the test dataset would be used to evaluate the performance of the algorithm.



