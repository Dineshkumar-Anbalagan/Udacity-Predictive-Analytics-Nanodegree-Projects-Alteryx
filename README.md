# Udacity-Predictive-Analytics-Nanodegree-Projects-Python
This repo has my alteryx version of predictive analytics nanodegree projects

## CRISP-DM

![image](https://user-images.githubusercontent.com/67826647/130355744-39c4d69b-f912-4212-a03d-f965b87d8e78.png)


# PROJECT 1 : [Predicting Diamond Prices](https://github.com/Dineshkumar-Anbalagan/Udacity-Predictive-Analytics-Nanodegree-Projects-Alteryx/tree/main/Project%201%20-%20Diamond_Project)
### Project Overview
A jewelry company wants to put in a bid to purchase a large set of diamonds, but is unsure how much it should bid. In this project, you will use the results from a predictive model to make a recommendation on how much the jewelry company should bid for the diamonds.

### US Number System
All numbers that will be presented in this Nanodegree program will be based on the US numbering system where 5,269 is "five thousand two hundred sixty nine" and 158.1 is "one hundred fifty eight point one" where 1 is a decimal number. This is very important so please take note of this.

### Project Details
A diamond distributor has recently decided to exit the market and has put up a set of 3,000 diamonds up for auction. Seeing this as a great opportunity to expand its inventory, a jewelry company has shown interest in making a bid. To decide how much to bid, the company’s analytics team used a large database of diamond prices to build a linear regression model to predict the price of a diamond based on its attributes. You, as the business analysts, are tasked to apply that model to make a recommendation for how much the company should bid for the entire set of 3,000 diamonds.

The following diagram represents the analysis at a high level. Since the model is already built, your analysis will focus on the right side of the diagram.

![diamond](https://user-images.githubusercontent.com/67826647/128141029-5e922a48-7b9b-4352-9bd3-284e00216cf6.png)

The linear regression model provides an equation that you can use to predict diamond prices for the set of 3,000 diamonds. The equation is below:

Price = -5,269 + 8,413 x Carat + 158.1 x Cut + 454 x Clarity

=====================================================================================

# PROJECT 2 : [Predicting Catalog Demand](https://github.com/Dineshkumar-Anbalagan/Udacity-Predictive-Analytics-Nanodegree-Projects-Alteryx/tree/main/Project%202%20-%20Predicting_Catalogue_Demand)

### The Business Problem
You recently started working for a company that manufactures and sells high-end home goods. Last year the company sent out its first print catalog, and is preparing to send out this year's catalog in the coming months. The company has 250 new customers from their mailing list that they want to send the catalog to.

Your manager has been asked to determine how much profit the company can expect from sending a catalog to these customers. You, the business analyst, are assigned to help your manager run the numbers. While fairly knowledgeable about data analysis, your manager is not very familiar with predictive models.

You’ve been asked to predict the expected profit from these 250 new customers. Management does not want to send the catalog out to these new customers unless the expected profit contribution exceeds $10,000.

### Details
* The costs of printing and distributing is $6.50 per catalog.
* The average gross margin (price - cost) on all products sold through the catalog is 50%.
* Make sure to multiply your revenue by the gross margin first before you subtract out the $6.50 cost when calculating your profit.
* Write a short report with your recommendations outlining your reasons why the company should go with your recommendations to your manager.

=====================================================================================

# PROJECT 3 : [Create an analytical dataset](https://github.com/Dineshkumar-Anbalagan/Udacity-Predictive-Analytics-Nanodegree-Projects-Alteryx/tree/main/Project%203%20-%20Creating%20Analytical%20Dataset)

### The Business Problem
Pawdacity is a leading pet store chain in Wyoming with 13 stores throughout the state. This year, Pawdacity would like to expand and open a 14th store. Your manager has asked you to perform an analysis to recommend the city for Pawdacity’s newest store, based on predicted yearly sales.

Your first step in predicting yearly sales is to first format and blend together data from different datasets and deal with outliers.

Your manager has given you the following information to work with:

1. The monthly sales data for all of the Pawdacity stores for the year 2010.
2. NAICS data on the most current sales of all competitor stores where total sales is equal to 12 months of sales.
3. A partially parsed data file that can be used for population numbers.
4. Demographic data (Households with individuals under 18, Land Area, Population Density, and Total Families) for each city and county in the state of Wyoming. For people who are unfamiliar with the US city system, a state contains counties and counties contains one or more cities.

### Map of Wyoming Counties

![image](https://user-images.githubusercontent.com/67826647/128142306-180a18dd-b621-4ea7-ad0f-fcd3ff1d6722.png)

=====================================================================================

# PROJECT 4 :[ Predicting default risk](https://github.com/Dineshkumar-Anbalagan/Udacity-Predictive-Analytics-Nanodegree-Projects-Alteryx/tree/main/Project%204%20-%20Predicting%20Default%20Risk)

### The Business Problem
You work for a small bank and are responsible for determining if customers are creditworthy to give a loan to. Your team typically gets 200 loan applications per week and approves them by hand.

Due to a financial scandal that hit a competitive bank last week, you suddenly have an influx of new people applying for loans for your bank instead of the other bank in your city. All of a sudden you have nearly 500 loan applications to process this week!

Your manager sees this new influx as a great opportunity and wants you to figure out how to process all of these loan applications within one week.

Fortunately for you, you just completed a course in classification modeling and know how to systematically evaluate the creditworthiness of these new loan applicants.

For this project, you will analyze the business problem using the Problem Solving Framework and provide a list of creditworthy customers to your manager in the next two days.


You have the following information to work with:

1. Data on all past applications
2. The list of customers that need to be processed in the next few days

=====================================================================================

# PROJECT 5 : [AB Test a New Menu Launch](https://github.com/Dineshkumar-Anbalagan/Udacity-Predictive-Analytics-Nanodegree-Projects-Alteryx/tree/main/Project%205%20-%20AB%20Test%20a%20New%20Menu%20Launch)

### The Business Problem
Round Roasters is an upscale coffee chain with locations in the western United States of America. The past few years have resulted in stagnant growth at the coffee chain, and a new management team was put in place to reignite growth at their stores.

The first major growth initiative is to introduce gourmet sandwiches to the menu, along with limited wine offerings. The new management team believes that a television advertising campaign is crucial to drive people into the stores with these new offerings.

However, the television campaign will require a significant boost in the company’s marketing budget, with an unknown return on investment (ROI). Additionally, there is concern that current customers will not buy into the new menu offerings.

To minimize risk, the management team decides to test the changes in two cities with new television advertising. Denver and Chicago cities were chosen to participate in this test because the stores in these two cities (or markets) perform similarly to all stores across the entire chain of stores; performance in these two markets would be a good proxy to predict how well the updated menu performs.

The test ran for a period of 12 weeks (2016-April-29 to 2016-July-21) where five stores in each of the test markets offered the updated menu along with television advertising.

The comparative period is the test period, but for last year (2015-April-29 to 2015-July-21).

You’ve been asked to analyze the results of the experiment to determine whether the menu changes should be applied to all stores. The predicted impact to profitability should be enough to justify the increased marketing budget: at least 18% increase in profit growth compared to the comparative period while compared to the control stores; otherwise known as incremental lift. In the data, profit is represented in the gross_margin variable.

You have been able to gather three data files to use for your analysis:

* Transaction data for all stores from 2015-January-21 to 2016-August-18
* A listing of all Round Roasters stores
* A listing of the 10 stores (5 in each market) that were used as test markets.

=====================================================================================

# PROJECT 6 : CAPSTONE PROJECT : [SEGMENTATION AND CLUSTERING](https://github.com/Dineshkumar-Anbalagan/Udacity-Predictive-Analytics-Nanodegree-Projects-Alteryx/tree/main/Project%206%20-%20Segmentation%20and%20Clustering)

### Task 1: Store Format for Existing Stores
Your company currently has 85 grocery stores and is planning to open 10 new stores at the beginning of the year. Currently, all stores use the same store format for selling their products. Up until now, the company has treated all stores similarly, shipping the same amount of product to each store. This is beginning to cause problems as stores are suffering from product surpluses in some product categories and shortages in others. You've been asked to provide analytical support to make decisions about store formats and inventory planning.

![one](https://video.udacity-data.com/topher/2019/August/5d47a326_man-climbing-up-in-grocery-store-115680/man-climbing-up-in-grocery-store-115680.jpg)

#### Task 1: Determining Store Format
To remedy the product surplus and shortages, the company wants to introduce different store formats. Each store format will have a different product selection in order to better match local demand. The actual building sizes will not change, just the product selection and internal layouts. The terms "formats" and "segments" will be used interchangeably throughout this project. You’ve been asked to:

* Determine the optimal number of store formats based on sales data.
    * Sum sales data by StoreID and Year
    * Use percentage sales per category per store for clustering (category sales as a percentage of total store sales).
    * Use only 2015 sales data.
    * Use a K-means clustering model.
* Segment the 85 current stores into the different store formats.
* Use the StoreSalesData.csv and StoreInformation.csv files.

### Task 2: Store Format for New Stores
The grocery store chain has 10 new stores opening up at the beginning of the year. The company wants to determine which store format each of the new stores should have. However, we don’t have sales data for these new stores yet, so we’ll have to determine the format using each of the new store’s demographic data.

![two](https://video.udacity-data.com/topher/2019/August/5d47a544_construction-in-toronto-may-2012/construction-in-toronto-may-2012.jpg)

Pretty sweet grocery store, right?

#### Task 2: Determine the Store Format for New Stores
You’ve been asked to:
* Develop a model that predicts which segment a store falls into based on the demographic and socioeconomic characteristics of the population that resides in the area around each new store.
* Use a 20% validation sample with Random Seed = 3 when creating samples with which to compare the accuracy of the models. Make sure to compare a decision tree, forest, and boosted model.
* Use the model to predict the best store format for each of the 10 new stores.
* Use the StoreDemographicData.csv file, which contains the information for the area around each store.
* Note: In a real world scenario, you could use PCA to reduce the number of predictor variables. However, there is no need to do so in this project. You can leave all predictor variables in the model.


### Task 3: Forecasting

Fresh produce has a short life span, and due to increasing costs, the company wants to have an accurate monthly sales forecast.

![three](https://video.udacity-data.com/topher/2019/August/5d479d48_22219503122-065a9f04be-b/22219503122-065a9f04be-b.jpg)

#### Task 3: Forecasting Produce Sales

You’ve been asked to prepare a monthly forecast for produce sales for the full year of 2016 for both existing and new stores. To do so, follow the steps below.

Note: Use a 6 month holdout sample for the TS Compare tool (this is because we do not have that much data so using a 12 month holdout would remove too much of the data)

Step 1: To forecast produce sales for existing stores you should aggregate produce sales across all stores by month and create a forecast.

Step 2: To forecast produce sales for new stores:

* Forecast produce sales (not total sales) for the average store (rather than the aggregate) for each segment.
* Multiply the average store produce sales forecast by the number of new stores in that segment.
* For example, if the forecasted average store produce sales for segment 1 for March is 10,000, and there are 4 new stores in segment 1, the forecast for the new stores in segment 1 would be 40,000.
* Sum the new stores produce sales forecasts for each of the segments to get the forecast for all new stores.
Step 3: Sum the forecasts of the existing and new stores together for the total produce sales forecast.


# GRADUATION CERTIFICATE : 

![graduation certificate](https://github.com/Dineshkumar-Anbalagan/Udacity-Predictive-Analytics-Nanodegree-Projects-Alteryx/blob/main/graduation%20certificate.png)
