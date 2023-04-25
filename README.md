# Promoting financial products to bank customers
![](IMAGES/Image1.jpg)
## Introduction
In 2016, a retail bank sold several products (mortgage account, savings account, and pension account) to its customers. It kept a record of all historical data, and this data is available for analysis and reuse. Following a merger in 2017, the bank has new customers and wants to launch some marketing campaigns.

The budget for the campaigns is limited. The bank wants to contact a customer and propose only one product

__The marketing department needs to decide:__

- Who should be contacted?
- Which one of the products should be proposed?
- Will such campaigns be profitable?

##  Problem statement 
__Predict which among the given bank products would be consumed by a customer__

<h3>Objectives</h3>
Our assignment is to develop clustering models through which we can  group customers in clusters and be able to know which of the given products could be recommended to them depending on the cluster they belong to. 
 

<h4>Segmentation workflow</h4>
From the historical data, we can train a machine learning product-based segmentation model on customer profile variables to group customers in categories also known as clusters and depending on the cluster a  customer belongs to, we can base on that information to know if  a customer would subscribe to a <b> mortgage </b> , <b> savings</b>, or <b> pension</b> account product.

You can apply this segmentation model to new customer data to predict for each new customer which of the above products  will they subscribe to. With this new data, you can decide which offers are proposed and Which product is offered to which customer.The solutions can be displayed, compared, and analyzed.

## Data sourcing
I got access to the data to address the problem above from a github repository.
The dataset contains 23 numerical columns namely:

'customer_id', 'age', 'age_youngest_child', 'debt_equity', 'gender','bad_payment', 'gold_card', 'pension_plan',
 'household_debt_to_equity_ratio', 'income', 'members_in_household','months_current_account', 'months_customer', 'call_center_contacts','loan_accounts', 'number_products', 'number_transactions','non_worker_percentage', 'white_collar_percentage', 'rfm_score','Mortgage', 'Pension', 'Savings', 'nb_products'.

Click <a href="https://raw.githubusercontent.com/vberaudi/utwt/master/unknown_behaviors.csv">HERE</a> to access 
the 2016 raw data.

You can also click <a href="https://raw.githubusercontent.com/vberaudi/utwt/master/unknown_behaviors.csv">HERE</a> to 
access the 2017 raw data.

## Data tranformation and cleaning.
1.  I had to first dropped the 'unnamed 0' column since it was not meaningful for our project.
2.  I removed duplicated data from the dataset 
3.  There was no missing data so imputation was performed
4.   

