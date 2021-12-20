### Traffic Sign Classification

A self driving car is an autonomous vehicle capable of operating on its own without any human intervation. It consists of several components to be automated like vehicle detection, road segmentation, pedestrian identification and so on. One such component is the identification of traffic sign automatically. Identifying the acccurate and exact traffic signs is an important component of self driving car. 

That's the reason we have picked this problem for you. In this problem, given images of different traffic signs, our task is to identify them. 

### Data Description


### images 

This folder contains all the images from train and test set.


### train.csv

This file contains the names of all the images in train set along with their labels. We have 5 different types of traffic signs.

| Variable | Definition |
| --- | --- |

|name | name of an image|
|label | type of traffic sign|


### test.csv

This file contains the names of all the images in test set and we have to predict their labels.

| Variable | Definition |
| --- | --- |

|name | name of an image|


### sample_submission.csv

This file contains the format in which you have to submit your solutions.

| Variable | Definition |
| --- | --- |

|name | name of an image|
|label | type of traffic sign|


### Evaluation Metric

1. The evaluation metric for this competition is macro F1 Score.
2. In order to clear this stage, your final score after submission should be more than or equal to 0.62

For further details of the hackathon and to make your submissions, go to this link:
https://datahack.analyticsvidhya.com/contest/traffic-sign-classification/