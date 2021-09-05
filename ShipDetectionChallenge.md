### Ship Detection Challenge

Ship or vessel detection has a wide range of applications, in the areas of maritime safety,  fisheries management, marine pollution, defence and maritime security, protection from piracy, illegal migration, etc. Keeping this in mind, a Governmental Maritime and Coastguard Agency is planning to deploy a computer vision based automated system to identify ship type only from the images taken by the survey boats. You have been hired as a consultant to build an efficient model for this project. There are 5 classes of ships to be detected which are as follows:

Cargo
Tanker
Military
Carrier
Cruise

### Data Description

There are 6252 images in train and 2680 images in test data.

There are three files provided to you, viz train.zip, test.csv and sample_submission.csv which have the following structure:

| Variable | Definition |
| --- | --- |
| image | Name of the image in the dataset (ID column) |
| category | Ship category code |

train.zip contains the images corresponding to both train and test set along with the true labels for train set images in train.csv

### Evaluation Metric

1. The Evaluation metric for this competition is weighted F1 Score.
2. In order to clear this stage, your final score after submission should be more than or equal to 0.90.

For further details of the hackathon and to make your submissions, go to this link: 
https://datahack.analyticsvidhya.com/contest/ship-detection/