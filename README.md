# Image Classification for a City Dog Show 
![alt text](C:\Users\lenovo\Downloads\archive\python-Scripts-\Image-Classifier-Deep-Learning-Project\doggydogworld.jpg"Dog Image.")


#### Description Problem statement:
The city is hosting a citywide dog show and you have volunteered to help the organizing committee with contestant registration. Every participant that registers must submit an image of their dog along with biographical information about their dog. The registration system tags the images based upon the biographical information.

Some people are planning on registering pets that aren’t actual dogs.
You need to use an already developed Python classifier to make sure the participants are dogs.

#### Principal Objectives

1. Correctly identify which pet images are of dogs (even if the breed is misclassified) and which pet images aren't of dogs.  
2. Correctly classify the breed of dog, for the images that are of dogs.  
3. Determine which CNN model architecture (ResNet, AlexNet, or VGG), "best" achieve objectives 1 and 2.  
4. Consider the time resources required to best achieve objectives 1 and 2, and determine if an alternative solution would have given a "good enough" result, given the amount of time each of the algorithms takes to run.

#### Test set results 
We had an inclusive dataset of a rotated image of a dog image and the rest were different animals and an image that was not of  an animal Below we have a summary for the uploaded CNN Model Architecture.

|Number of Images||---||4|
|Number of Dog Images||---||3|
|Number of Not-a-Dog Images||---||1|



|CNN Model Architecture|pct_match|pct_correct_dogs|pct_correct_breed|pct_correct_notdogs|
|---|---|---|---|---|---|
|VGG|50.0%|0.0%|100.0%|66.7%|
|AlexNet|50.0%|0.0%|100.0%|66.7%|
|RestNet|50.0%|0.0%|100.0%|66.7%|



#### Model Deep Learning (CNN)
We use a deep learning model called a convolutional neural network (CNN).  We use a CNN that has already learned the features from a giant dataset of 1.2 million images called ImageNet. Types of CNNs architectures we use with this project are (AlexNet, VGG, and ResNet) and we determine which is best for project application.

#### Project Results 
The program provided us with objectives 1 and 2 when  the program provided us with results as provided below.

For objective 1, notice that both VGG and AlexNet correctly identify images of "dogs" and "not-a-dog" 100% of the time.
For objective 2, VGG provides the best solution because it classifies the correct breed of dog over 90% of the time.
![alt text](C:\Users\lenovo\Downloads\Udacity_image_dog_classifier_project\projectresulps.jpg "Model Results")

Given our results, the "best" model architecture is VGG. It outperformed both of the other architectures when considering both objectives 1 and 2. You will notice that ResNet did classify dog breeds better than AlexNet, but only VGG and AlexNet were able to classify "dogs" and "not-a-dog" at 100% accuracy. The model VGG was the one that was able to classify "dogs" and "not-a-dog" with 100% accuracy and had the best performance regarding breed classification with 93.3% accuracy.

#### Conclusion 
The results indicate that more images for better classification of images is warranted, to better the classifier. 
Fine tune the models is also an option we might consider after the addition of images. 
#### References
Udacity Nanodegree Program Dog image classification Project. 
