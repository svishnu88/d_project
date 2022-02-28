## Supplement Sales Prediction

### Problem Statement

Your Client WOMart is a leading nutrition and supplement retail chain that offers a comprehensive range of products for all your wellness and fitness needs. 

WOMart follows a multi-channel distribution strategy with 350+ retail stores spread across 100+ cities. 

Effective forecasting for store sales gives essential insight into upcoming cash flow, meaning WOMart can more accurately plan the cashflow at the store level.

Sales data for 18 months from 365 stores of WOMart is available along with information on Store Type, Location Type for each store, Region Code for every store, Discount provided by the store on every day, Number of Orders everyday etc.

Your task is to predict the store sales for each store in the test set for the next two months.

### Data Dictionary

You are provided with 3 files - train.csv, test.csv and sample_submission.csv

1. train.csv

| Variable | Definition |
| --- | --- |
| ID | Unique Identifier for a row |
| Store_id | Unique id for each Store |
| Store_Type | Type of the Store |
| Location_Type | Type of the location where Store is located |
| Region_Code | Code of the Region where Store is located |
| Date | Information about the Date |
| Holiday | If there is holiday on the given Date, 1 : Yes, 0 : No |
| Discount | If discount is offered by store on the given Date, Yes/ No |
| #Orders | Number of Orders received by the Store on the given Day |
| Sales | Total Sale for the Store on the given Day |

2. test.csv

| Variable | Definition |
| --- | --- |
| ID | Unique Identifier for a row |
| Store_id | Unique id for each Store |
| Store_Type | Type of the Store |
| Location_Type | Type of the location where Store is located |
| Region_Code | Code of the Region where Store is located |
| Date | Information about the Date |
| Holiday | If there is holiday on the given Date, 1 : Yes, 0 : No |
| Discount | If discount is offered by store on the given Date, Yes/ No |

3. sample_submission.csv

| Variable | Definition |
| --- | --- |
| ID | Unique Identifier for a row |
| Sales | Total Sale for the Store on the given Day |

### Evaluation Metric

1. The evaluation metric for this competition is MSLE * 1000.
2. In order to clear this stage, your final score after submission should be less than or equal to 230.