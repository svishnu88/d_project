### Auto Tagging Research Articles 

Researchers have access to large online archives of scientific articles. As a consequence, finding relevant articles has become more difficult. Tagging provides a way to give token of identification to research articles which facilitates recommendation and search process. 

Given the abstract and titles for a set of research articles, predict the topics for each article included in the test set. 
Note that a research article can possibly have more than 1 topics. The research article abstracts are sourced from the following 6 topics: 

1. Computer Science

2. Mathematics

3. Physics

4. Statistics

5. Quantitative Biology

6. Quantitative Finance

### Data Description

#### train.csv

| Variable | Definition |
| --- | --- |
| ID | Unique ID for each article |
| TITLE | Title of the research article |
| ABSTRACT | Abstract of the research article |
| Computer Science | Whether article belongs to topic computer science (1/0) |
| Physics | Whether article belongs to topic physics (1/0) |
| Mathematics | Whether article belongs to topic Mathematics (1/0) |
| Statistics | Whether article belongs to topic Statistics (1/0) |
| Quantitative Biology | Whether article belongs to topic Quantitative Biology (1/0) |
| Quantitative Finance | Whether article belongs to topic Quantitative Finance (1/0) |

#### test.csv

| Variable | Definition |
| --- | --- |
| ID | Unique ID for each article |
| TITLE | Title of the research article |
| ABSTRACT | Abstract of the research article |

#### sample_submission.csv

| Variable | Definition |
| --- | --- |
| ID | Unique ID for each article |
| Computer Science | Whether article belongs to topic computer science (1/0) |
| Physics | Whether article belongs to topic physics (1/0) |
| Mathematics | Whether article belongs to topic Mathematics (1/0) |
| Statistics | Whether article belongs to topic Statistics (1/0) |
| Quantitative Biology | Whether article belongs to topic Quantitative Biology (1/0) |
| Quantitative Finance | Whether article belongs to topic Quantitative Finance (1/0) |

### Evaluation Metric

1. The evaluation metric for this competition is micro F1 Score.
2. In order to clear this stage, your final score after submission should be more than or equal to 0.80

For further details of the hackathon and to make your submissions, go to this link:
https://datahack.analyticsvidhya.com/contest/topic-modeling-for-research-papers/