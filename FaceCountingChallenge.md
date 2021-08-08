## Face Counting Challenge

### Problem Statement

People detection and head counting is one of the classical albeit challenging computer vision application. For this problem, given a group selfie/photo, you are required to count the number of heads present in the picture. You are provided with a training set of images with coordinates of bounding box and head count for each image and need to predict the headcount for each image in the test set.

### Data Dictionary

You are provided with 3 files:

a. train.zip: Contains 2 csvs and 1 folder containing image data

    1. train.csv - ['Name', 'HeadCount'] (contains headcount value for each training image)
    2. bbox_train.csv - ['Name', 'width', 'height' , 'xmin', 'ymin', 'xmax', 'ymax', 'class'] (contains co-ordinates of each head in the train image, located by the formation of a bound-box around the head)
    3. image_data - This contains images for both the train and the test set

b. test.csv - ['Name'] (contains only name of test images)

c. sample_submission.csv - ['Name', 'HeadCount'] (contains format for a valid submission)

### Evaluation Metric

1. The evaluation metric for this competition is rmse * 100.
2. In order to clear this stage, your final score after submission should be less than or equal to 150.

For further details of the hackathon and to make your submissions, go to this link: 
https://datahack.analyticsvidhya.com/contest/face-counting-challenge/