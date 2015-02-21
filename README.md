# Kaggle
Solving Kaggle Problems


Detect Keypoints on "Face Images":

Problem Statement- 
Given an image of a face, automatically locate where these keypoints are located.

Mastered the kaggle intro:
* Load Train and test data set to R.
* Create R data frames for both data sets.
* Reformat image column to a seperate data frame of 9216 (96*96) integer columns.
* Convert the image data frame to a matrix that can be fed to image function of R (reverse).
* Visualise the image, locate the keypoints with colors on the image.

Cracking the First Benchmark:
* CAlculate the mean of all keypoints of the training set.
* Use the mean values from above to predict the keypints for test images.

Scope for improvements:
* Optimise the means from train set by detecting and removing the outliers from train set.
* Find a quantifier other than the mean for prediction.

Next Step:
* Explore Regression and Neural Networks techniques for face keypoint detection.
* Identify methods from Research Papers in the repo.








