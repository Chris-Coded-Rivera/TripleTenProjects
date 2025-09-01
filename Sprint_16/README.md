# ***Interconnect*** Customer Retainment 

Problem: ***Interconnect*** has found their customers churning and need to find a solution before imlementing any campaigns to add new customers as it would not make sense if over 20% of their customers have termimnated their service.

Proposal: Create a model that predicts which customers are going to termiante their service to give the company a chance to intervene and keep the customer.

This project highlights the importance of viewing the data and creating a work plan according to the findings within the data.

After the work plan, solution code must be created to complete the task. We'll find that sometimes our plan doesn't go according to how we've written but solutions must be found in order to maximize results. 

The Solution Report is included detailing a work report review, troubleshooting, and final model quality.

The dataset used for this project can be downloaded here:
<a href='https://practicum-content.s3.us-west-1.amazonaws.com/data-eng/datasets/final_provider.zip'>DOWNLOAD</a>

If that link does not work a copy of the files can be found within this repository in the final_provider folder
## Data Description 
There are 4 datasets included within the downloadeable data:

* contract.csv` - contract information

* personal.csv - client's personal data

* internet.csv - information about Internet services

* phone.csv - information about telephone services

All files contain the `customerID` column that serves as a primary key for joining the datasets.

The contract information is valid as of February 1, 2020

The target feature is `EndDate` with 'No' values. You will find a new feature was created in this project to use as a target feature instead. The primary metric used to evaluate the models is 'ROC-AUC' score.

Feel free to replicate and/or build a better model than the final model created in this repo.

Enjoy! 
