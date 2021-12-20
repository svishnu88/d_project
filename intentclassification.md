###intent classification

One of the top data science companies wants to deploy the chatbot to automatically respond to the queries asked by user. Inorder to achieve this, one of the primary steps is to identify the intent of a query. Intent Classification is one of the prominent steps while building the chatbot. So, as a data scientist, you are given the task to build the high performance model for classifying the queries into one of the these categories: techniques, tools, career, resources.

### Data Description

### train.csv

| Variable | Definition |
| --- | --- |

| Id | Unique Id of a text|
| text | Query of an user|
|intent | intent of a query|


### test.csv

| Variable | Definition |
| --- | --- |
| Id | Unique Id of a text|
| text | Query of an user|



### sample_submission.csv

| Variable | Definition |
| --- | --- |
| Id | Unique Id of a text|
| intent | intent of a query|


### Evaluation Metric

1. The evaluation metric for this competition is macro F1 Score.
2. In order to clear this stage, your final score after submission should be more than or equal to 0.62

For further details of the hackathon and to make your submissions, go to this link:
https://datahack.analyticsvidhya.com/contest/intent-classification/