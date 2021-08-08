## Web Page Classification

### Problem Statement

Classification of Web page content is vital to many tasks in Web information retrieval such as maintaining Web directories and focused crawling. The uncontrolled nature of Web content presents additional challenges to Web page classification as compared to traditional text classification, however the interconnected nature of hypertext also provides features that can assist the process.

Here the task is to classify the web pages to the respective classes it belongs to, in a single label classification setup (Each webpage can belong to only 1 class).

Basically given the complete html and url, predict the tag a web page belongs to out of 9 predefined tags as given below:

1. People profile
2. Conferences/Congress
3. Forums
4. News article
5. Clinical trials
6. Publication
7. Thesis
8. Guidelines
9. Others

### Data Dictionary

You are provided with 3 files:

1. web_page_train.csv

| Variable | Definition |
| --- | --- |
| Webpage_id | Unique ID for the Web page |
| Tag | (Target) Tag (Class) of the Web page |
| text | Web page data in HTML |

2. web_page_test.csv

| Variable | Definition |
| --- | --- |
| Webpage_id | Unique ID for the Web page |
| text | Web page data in HTML |

3. sample_submission.csv

| Variable | Definition |
| --- | --- |
| Webpage_id | Unique ID for the Web page |
| Tag | (Target) Tag (Class) of the Web page |

### Evaluation Metric

1. The evaluation metric for this competition is weighted F1 score.   
2. In order to clear this stage, your final score after submission should be more than or equal to 0.92.

For further details of the hackathon and to make your submissions, go to this link: 
https://datahack.analyticsvidhya.com/contest/web-page-classification/