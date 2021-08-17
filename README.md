# Service_center_DE

Goal - Perform data analysis and find insights.

This notebook is divided into 3 parts

* Data Cleaning
* Feature Engineering
* Data Analysis

Next steps for Predictions (Not applied here as goal was not to predict any values but find trends)
* Data Preparation for the model insertion
* K-Fold cross validation to reduce overfitting and creating train/valid/test datasets
* Model creation and training train dataset
* finding accuracy on the test dataset
* Make changes and implement different models
* repeat till accuracy improves


Data Definitions:
* Asst_id – an identifier for each individual machine sold
* Product_type – class of product that describes the asset
* Region – region where the asset is located
* Country – country where the asset is located
* Mnfcture_wk – week when product was manufactured
* Contract_st – week when warranty became active
* Contract_end – week when warranty expires
* Contact_wk – week when customer contacted Dell about a problem
* Contact_type – way that customer contacted Dell
* Issue_type – type of problem identified by customer
* Topic_category – type of problem as classified by the tech support agent
* Parts_sent – what parts were sent to fix the problem
* Repair_type – if a part was required, this is a hard repair; otherwise, a soft repair
* Repeat_ct – how many additional visits were required to fix the problem, past the first one
* Parts_ct – how many parts were sent to fix the problem
* Agent_tenure_indays – how long the tech support agent has worked in Dell tech support
* Contact_manager_flg – did the tech support agent have to bring in a manager to solve the problem
* Diagnostics – were agents compliant with diagnostic usage
* Repeat_parts_sent – which parts were sent on additional visit

