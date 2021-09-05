### Scene Classification Challenge

There has been a tremendous increase in the applications of Computer Vision. The applications of Computer Vision range from smart cameras and video surveillance to robotics, transportation and more.

How do we, humans, recognize a forest as a forest or a mountain as a mountain? We are very good at categorizing scenes based on the semantic representation and object affinity, but we know very little about the processing and encoding of natural scene categories in the human brain. In this Hackathon, you are provided with a dataset of ~25k images from a wide range of natural scenes from all around the world. Your task is to identify which natural scene can the image be categorized into. Below is the description of different categories of the scenes in which the images can be classified:

| Label | Description |
| --- | --- |
| 0 | Buildings |
| 1 | Forest |
| 2 | Glacier |
| 3 | Mountain |
| 4 | Sea |
| 5 | Street |

There are 17034 images in train and 7301 images in test data.

### Data Description

There are three files provided to you:
1. train.zip
2. test.csv
3. sample_submission.csv

train.zip contains the images corresponding to both train and test set along with the true labels for train set images in train.csv

test.csv contains the names of images for the test set

sample_submission.csv have the following structure:

| Variable | Definition |
| --- | --- |
| image_name | Name of the image in the dataset (ID column) |
| label | Category of natural scene (target column) |

### Evaluation Metric

1. The evaluation metric for this competition is accuracy score.
2. In order to clear this stage, your final score after submission should be more than or equal to 0.945

For further details of the hackathon and to make your submissions, go to this link: 
https://datahack.analyticsvidhya.com/contest/web-page-classification-2/