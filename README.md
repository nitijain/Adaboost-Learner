# Adaboost-Learner
This repository implements the famous Viola  Jones  Algorithm from scratch for face detection. Face detection is one of the challenging computer vision problem which involves detection and identification of faces in a given image. Some of the challenges in face detection include illumination, posture, occlusion etc.  In this report, the Viola Jones algorithm is mainly divided into three major parts, namely Extracting Haar Features, Finding the best haar Features on training data, and Finally, using Ada-Boost to develop the face detector. 

The dataset is not included here. Should be under the name Dataset/ and contain testset and trainset
The repository contains the following files
* Pattern Recognition Project.ipynb - This file contains the logic for the 3 parts + bonus as asked in the question
* weak_classifiers_t1.pkl - Classifier model for round = 1
* weak_classifiers_t3.pkl	 - Classifier model for round = 3
* weak_classifiers_t5.pkl	 - Classifier model for round = 5
* weak_classifiers_t10.pkl - Classifier model for round = 10
* weak_classifiers_t25.pkl	 - Classifier model for round = 25
* weak_classifiers_t50.pkl  - Classifier model for round = 50
* weak_classifiers_fn5.pkl - Classifier model for 5 rounds to improve FN 
* weak_classifiers_fp5.pkl - Classifier model for 5 rounds to improve FP
* data_test-Y - data file containing test y labels (extracted)
* data_train-Y- data file containing train y labels (extracted)
* data_test-X - data file containing test image's features (generated in code, couldn't be attached due to the limitation of size on Github)
* data_train-Y- data file containing train image's features (generated in code, couldn't be attached due to the limitation of size on Github)
* png files - contain the feature plotted test images



