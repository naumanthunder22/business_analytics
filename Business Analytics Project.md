||BUSINESS ANALYTICS |
| :- | - |
|||
**PROJECT REPORT  ![](Aspose.Words.8f440b01-fbd5-4b80-882d-708c4c851d2b.001.png)![](Aspose.Words.8f440b01-fbd5-4b80-882d-708c4c851d2b.002.png)**

**BBA-7B**  

Business Analytics  ![](Aspose.Words.8f440b01-fbd5-4b80-882d-708c4c851d2b.003.png)![](Aspose.Words.8f440b01-fbd5-4b80-882d-708c4c851d2b.004.png)![](Aspose.Words.8f440b01-fbd5-4b80-882d-708c4c851d2b.005.jpeg)

PROJECT REPORT 

CLASSIFICATION  

Submitted To  

DR. AAMER HANIF  

Submitted By ![](Aspose.Words.8f440b01-fbd5-4b80-882d-708c4c851d2b.006.png)![](Aspose.Words.8f440b01-fbd5-4b80-882d-708c4c851d2b.007.jpeg)

**MUHAMMAD ADIL (180358) - GROUP LEADER SYEDA KASHFE ZEHRA KAZMI (180355)** 

**LAIBA AMJAD (180343)**  

Date 

09-12-2021 

A Project Report for Fulfillment of the Requirement of Subject Business Analytics![](Aspose.Words.8f440b01-fbd5-4b80-882d-708c4c851d2b.008.png)

**TABLE OF CONTENTS** 

[TASK OVERVIEW & PRE-PROCESSING ...................................................................................................................... 8 ](file:///C:/Users/HP_ENVY/Downloads/kashaf_data/Business%20Analytics/Muhammad%20Adil,%20Syeda%20Kashfe%20Zehra,%20Laiba%20Amjad.docx%23_Toc89974420)

1. [**Introduction** ............................................................................................................................................ 8 ](#_page7_x47.00_y136.00)
1. [**Project Goal** ............................................................................................................................................. 8 ](#_page7_x47.00_y226.00)
1. [**Seed Value**............................................................................................................................................... 8 ](#_page7_x47.00_y266.00)
1. [**Dataset Loading and Splitting** .................................................................................................................. 8 ](#_page7_x47.00_y329.00)

[DATA EXPLORATION .............................................................................................................................................. 10 ](file:///C:/Users/HP_ENVY/Downloads/kashaf_data/Business%20Analytics/Muhammad%20Adil,%20Syeda%20Kashfe%20Zehra,%20Laiba%20Amjad.docx%23_Toc89974425)

1. [**Introduction** .......................................................................................................................................... 10 ](#_page9_x83.00_y113.00)
1. [**How many observations are there in the dataset?** ................................................................................ 10 ](#_page9_x47.00_y153.00)
1. [**What percentage of clients defaulted from the loan?** ........................................................................... 10 ](#_page9_x47.00_y370.00)
1. [**What percentage of employed clients are loan defaulters?** .................................................................. 11 ](#_page10_x47.00_y56.00)
1. [**What percentage of unemployed clients are loan defaulters?** .............................................................. 11 ](#_page10_x47.00_y314.00)
1. [**What percentage of married clients are loan defaulters?** ..................................................................... 11 ](#_page10_x47.00_y571.00)
1. [**What are the top 3 jobs according to employee counts in the dataset?**................................................ 12 ](#_page11_x47.00_y304.00)
1. [**Which 3 job types have the most loan defaulters?**................................................................................ 13 ](#_page12_x47.00_y41.00)
1. [**What percentage of clients have tertiary education?**............................................................................ 13 ](#_page12_x47.00_y290.00)

[LOGISTIC REGRESSION MODEL .............................................................................................................................. 14 ](file:///C:/Users/HP_ENVY/Downloads/kashaf_data/Business%20Analytics/Muhammad%20Adil,%20Syeda%20Kashfe%20Zehra,%20Laiba%20Amjad.docx%23_Toc89974437)

1. [**Introduction** .......................................................................................................................................... 14 ](#_page13_x83.00_y131.00)
1. [**List all variables in your model which are significant (have one or more   *).**........................................ 14 ](#_page13_x47.00_y171.00)
1. [**Interpret the coefficient of ‘lateOver90days’ and ‘Jobunemployed’ from  your model.**........................ 16 ](#_page15_x47.00_y244.00)
1. [**Score the model on the test data and provide the confusion matrix for  the test data using the model.** 16 ](#_page15_x47.00_y456.00)
5. [**Find the accuracy, precision and recall for this algorithm on the test set.**............................................. 17 ](#_page16_x47.00_y41.00)

[DECISION TREE - CART MODEL .............................................................................................................................. 19 ](file:///C:/Users/HP_ENVY/Downloads/kashaf_data/Business%20Analytics/Muhammad%20Adil,%20Syeda%20Kashfe%20Zehra,%20Laiba%20Amjad.docx%23_Toc89974445)

1. [**Introduction** .......................................................................................................................................... 19 ](#_page18_x83.00_y115.00)
1. [**Which variable is the root and how many splits are there in the tree?** ................................................. 19 ](#_page18_x47.00_y155.00)
1. [**Provide the confusion matrix for the test data.**..................................................................................... 20 ](#_page19_x47.00_y385.00)
1. [**Find the accuracy, precision and recall for this algorithm on the test set.**............................................. 20 ](#_page19_x47.00_y603.00)
1. [**Write all rules extracted from the decision tree.** ................................................................................... 22 ](#_page21_x47.00_y426.00)

[NAÏVE BAYESIAN CLASSIFICATION MODEL ............................................................................................................. 24 ](file:///C:/Users/HP_ENVY/Downloads/kashaf_data/Business%20Analytics/Muhammad%20Adil,%20Syeda%20Kashfe%20Zehra,%20Laiba%20Amjad.docx%23_Toc89974453)

1. [**Introduction** .......................................................................................................................................... 24 ](#_page23_x83.00_y121.00)
1. [**Provide the confusion matrix for the test data.**..................................................................................... 24 ](#_page23_x47.00_y159.00)
1. [**Find the accuracy, precision and recall for this algorithm on the test  dataset.**..................................... 24 ](#_page23_x47.00_y439.00)

[RANDOM FOREST MODEL ..................................................................................................................................... 27 ](file:///C:/Users/HP_ENVY/Downloads/kashaf_data/Business%20Analytics/Muhammad%20Adil,%20Syeda%20Kashfe%20Zehra,%20Laiba%20Amjad.docx%23_Toc89974459)![](Aspose.Words.8f440b01-fbd5-4b80-882d-708c4c851d2b.009.png)

1. [**Introduction** .......................................................................................................................................... 27 ](#_page26_x83.00_y131.00)
1. [**Score the model on the test data and provide the confusion matrix for  the test data.** ........................ 27 ](#_page26_x47.00_y171.00)
1. [**Find the accuracy, precision and recall for this algorithm on the test set.**............................................. 27 ](#_page26_x47.00_y471.00)

[K NEAREST NEIGHBOR MODEL .............................................................................................................................. 30 ](file:///C:/Users/HP_ENVY/Downloads/kashaf_data/Business%20Analytics/Muhammad%20Adil,%20Syeda%20Kashfe%20Zehra,%20Laiba%20Amjad.docx%23_Toc89974465)

1. [**Introduction** .......................................................................................................................................... 30 ](#_page29_x83.00_y131.00)
1. [**Pre-Requisite Step** ................................................................................................................................. 30 ](#_page29_x47.00_y171.00)
1. [**Provide the confusion matrix for the test data.**..................................................................................... 30 ](#_page29_x47.00_y243.00)
1. [**Find the accuracy, precision and recall for this algorithm on the test set.**............................................. 31 ](#_page30_x47.00_y522.00)
1. [**Which value of K among these provides the maximum accuracy.** ......................................................... 35 ](#_page34_x47.00_y41.00)
6. [**Compare all model evaluation metrics (accuracy etc.) obtained by the  five algorithms by making a comparison table and comment on the  findings.**............................................................................................. 35 ](#_page34_x47.00_y91.00)

[CLASSIFYING UNKNOWN DATA ............................................................................................................................. 37 ](file:///C:/Users/HP_ENVY/Downloads/kashaf_data/Business%20Analytics/Muhammad%20Adil,%20Syeda%20Kashfe%20Zehra,%20Laiba%20Amjad.docx%23_Toc89974474)

[**8.1**  **Question**................................................................................................................................................ 37 ](#_page36_x83.00_y131.00)[RECOMMENDATIONS TO CEO ............................................................................................................................... 39 ](file:///C:/Users/HP_ENVY/Downloads/kashaf_data/Business%20Analytics/Muhammad%20Adil,%20Syeda%20Kashfe%20Zehra,%20Laiba%20Amjad.docx%23_Toc89974478)

1. [**Question**................................................................................................................................................ 39 ](#_page38_x83.00_y121.00)
1. [**Conclusion** ............................................................................................................................................. 39 ](#_page38_x47.00_y229.00)
1. [**Recommendations** ................................................................................................................................ 39 ](#_page38_x47.00_y369.00)
4. [**Supplementary Method** ........................................................................................................................ 40 ](#_page39_x47.00_y50.00)
4. [**Final Thoughts on New Method** ............................................................................................................ 41 ](#_page40_x47.00_y505.00)![](Aspose.Words.8f440b01-fbd5-4b80-882d-708c4c851d2b.009.png)

**LIST OF FIGURES** 

[**Figure 1: Train Data (70%) after Splitting** ................................................................................................................ 8 ](#_page7_x47.00_y667.00)[**Figure 2: Test Data (30%) after Splitting** ................................................................................................................. 9 ](#_page8_x47.00_y272.00)[**Figure 3: Dataset Overview**................................................................................................................................... 10 ](#_page9_x47.00_y331.00)[**Figure 4: Frequency Table for Default** ................................................................................................................... 10 ](#_page9_x47.00_y680.00)[**Figure 5: Cross Tab for Default and Job variables (checking employed clients)** .................................................... 11 ](#_page10_x47.00_y265.00)[**Figure 6:Cross Tab for Default and Job variables (checking unemployed clients)** ................................................. 11 ](#_page10_x47.00_y522.00)[**Figure 7: Cross Tab for Default and Status variables (checking married clients)** ................................................... 12 ](#_page11_x47.00_y279.00)[**Figure 8: Summary of Job variable** ........................................................................................................................ 12 ](#_page11_x47.00_y692.00)[**Figure 9: Cross Tab for Default and Job variables (checking most loan defaulters)**............................................... 13 ](#_page12_x47.00_y265.00)[**Figure 10: Frequency Table for Education** ............................................................................................................. 13 ](#_page12_x47.00_y692.00)![](Aspose.Words.8f440b01-fbd5-4b80-882d-708c4c851d2b.009.png)

**LIST OF TABLES** 

[**Table 1: Comparison of all Model Evaluation Metrics**........................................................................................... 35 ](#_page34_x47.00_y157.00)[**Table 2: Comparison of Models before and after K-Fold Cross Validation** ............................................................ 36 ](#_page35_x47.00_y100.00)[**Table 3: Comparison of Predictions for given Test Dataset**................................................................................... 38 ](#_page37_x47.00_y85.00)![](Aspose.Words.8f440b01-fbd5-4b80-882d-708c4c851d2b.009.png)

TASK OVERVIEW & PRE-PROCESSING 

1. **Introduction** 

The  data  provided  for  this  project  is  from  the  loans  department  of  a  bank.  Based upon  certain  attributes,  it  is  given  if  there  was  a  default  by  the  customer  on  the  given  loan  or not.  Hence  it  is  a  classification  problem  requiring  you  to  apply  relevant  techniques  to  classify customers as defaulters or otherwise.

2. **Project Goal**

To predict if the customer will default on loan provided by the bank. 

3. **Seed Value** 

As given in the document that each group will use the seed value for random sampling as Roll No of the group leader. So, seed value in our case is **180358**. 

4. **Dataset Loading and Splitting**

We have loaded the dataset and then performed following steps:

- We switched to variables window and then converted the Data Class of “**Default**” variable to “**Factor**” by using “**Make Factor**” option. 
- We split the dataset using “**Random Split**” with percentage of 70% (for training) and 30% (for testing) using 180358 as seed value as shown in[ Figure 1 ](#_page7_x47.00_y667.00)and[ Figure 2 ](#_page8_x47.00_y272.00)below. 

![](Aspose.Words.8f440b01-fbd5-4b80-882d-708c4c851d2b.010.png)

**Figure 1: Train Data (70%) after Splitting ![](Aspose.Words.8f440b01-fbd5-4b80-882d-708c4c851d2b.009.png)**

![](Aspose.Words.8f440b01-fbd5-4b80-882d-708c4c851d2b.011.png)

**Figure 2: Test Data (30%) after Splitting ![](Aspose.Words.8f440b01-fbd5-4b80-882d-708c4c851d2b.009.png)**

DATA EXPLORATION 

1. **Introduction**

The chapter is addressing questions related to data exploration of the dataset.

2. **How many observations are there in the dataset?** 

There are 75,755 observations in the dataset as mentioned in[ Figure 3.](#_page9_x47.00_y331.00) 

![](Aspose.Words.8f440b01-fbd5-4b80-882d-708c4c851d2b.012.png)

**Figure 3: Dataset Overview** 

3. **What percentage of clients defaulted from the loan?** 

Defaulted clients are 9.5386% (7226) of the total cases. Summary of factor variable i.e.  “Default” is shown in[ Figure 4.](#_page9_x47.00_y680.00)  

![](Aspose.Words.8f440b01-fbd5-4b80-882d-708c4c851d2b.013.png)

**Figure 4: Frequency Table for Default ![](Aspose.Words.8f440b01-fbd5-4b80-882d-708c4c851d2b.009.png)**

4. **What percentage of employed clients are loan defaulters?** 

There are 12.2198% (883) employed clients who are loan defaulters. 

![](Aspose.Words.8f440b01-fbd5-4b80-882d-708c4c851d2b.014.png)

**Figure 5: Cross Tab for Default and Job variables (checking employed clients)** 

5. **What percentage of unemployed clients are loan defaulters?** 

There are 63.7282% (4605) unemployed clients who are loan defaulters. 

![](Aspose.Words.8f440b01-fbd5-4b80-882d-708c4c851d2b.015.png)

**Figure 6:Cross Tab for Default and Job variables (checking unemployed clients)** 

6. **What percentage of married clients are loan defaulters?** 

There are 59.8671% (4326) married clients who are loan defaulters. ![](Aspose.Words.8f440b01-fbd5-4b80-882d-708c4c851d2b.009.png)

![](Aspose.Words.8f440b01-fbd5-4b80-882d-708c4c851d2b.016.png)

**Figure 7: Cross Tab for Default and Status variables (checking married clients)** 

7. **What are the top 3 jobs according to employee counts in the dataset?** 

Top three jobs according to employee counts are Management (13,078), Blue-Collar (19,660) and Technician (11,864). 

![](Aspose.Words.8f440b01-fbd5-4b80-882d-708c4c851d2b.017.png)

**Figure 8: Summary of Job variable ![](Aspose.Words.8f440b01-fbd5-4b80-882d-708c4c851d2b.009.png)**

8. **Which 3 job types have the most loan defaulters?** 

Job  types  encompassing  most  loan  defaulter  are  Self-employed  (883),  Services  (390)  and Technicians (273). 

![](Aspose.Words.8f440b01-fbd5-4b80-882d-708c4c851d2b.018.png)

**Figure 9: Cross Tab for Default and Job variables (checking most loan defaulters)** 

9. **What percentage of clients have tertiary education?** 

There are 24.599% (18635) clients having tertiary education. 

![](Aspose.Words.8f440b01-fbd5-4b80-882d-708c4c851d2b.019.png)

**Figure 10: Frequency Table for Education ![](Aspose.Words.8f440b01-fbd5-4b80-882d-708c4c851d2b.009.png)**

LOGISTIC REGRESSION MODEL 

1. **Introduction**

The chapter is addressing questions related to Logistic Regression Model.

2. **List all variables in your model which are significant (have one or more  \*).** 

After analysis of variable significance, we come to know that 15 variables are most significance, 1 variable is categorized as less significant and 2 variables are least significant. Whereas 6 variables are categorized as non-significant. Details of significant variables are shown below:** 

- **Most Significant Variables (\*\*\*):** All of these variables have **P-Value** i.e., Pr(>|z|) less than 

0.001. we know that P-value should be less than 0.05 for significant variables and .001 is much less than 0.05, which proves its significance.** 

- Credit Balance in Percentage  
- Late Up to 60 Days  
- Late 60 to 90 Days  
- Late Over 90 Days  
- Income 
- No Of Open Loans 
- Age 
- Job: Blue-collar 
- Job: Entrepreneur 
- Job: Retired 
- Job: Self Employed 
- Job: Unemployed 
- Education: Secondary 
- Education: Tertiary 
- Education: Unknown 
- **Less Significant Variables (\*\*):** All of these variables have **P-Value** i.e., Pr(>|z|) less than 0.001.** 
  - Job: Services 
- **Least Significant Variables (\*):** Variables under this category have **P-Value** i.e., Pr(>|z|) less than 0.018 and 0.0313 respectively.** 
  - No Of Home Loans 
  - Job: Student 
- **Non-Significant Variables:**  All variables having **P-Value** i.e., Pr(>|z|) greater than 0.05 are categorized as non-significant variables.** 
- Debt in Percentage  
- Dependents 
- Job: Management 
- Job: Technician  ![](Aspose.Words.8f440b01-fbd5-4b80-882d-708c4c851d2b.009.png)
- Status: Married 
- Status: Single ![](Aspose.Words.8f440b01-fbd5-4b80-882d-708c4c851d2b.009.png)

![](Aspose.Words.8f440b01-fbd5-4b80-882d-708c4c851d2b.020.png)

![](Aspose.Words.8f440b01-fbd5-4b80-882d-708c4c851d2b.021.png)

3. **Interpret the coefficient of ‘lateOver90days’ and ‘Jobunemployed’ from your model.** 

Both the coefficients i.e., lateOver90days and Jobunemployed fall under category of significant variables  i.e.,  **P-Value**  Pr(>|z|)  less  than  0.001.  Moreover, "std.error" of  lateOver90days  and Jobunemployed are 0.1381 and 0.1309 respectively. The "std.error" is the standard deviation of the coefficient point estimate in the Logistic Regression Model. It is a measure of uncertainty about coefficient point estimate. if it is too large, then we have a coefficient point estimate calculated with a lot of imprecisions. The larger the "std. error", the larger the p-value. 

Above-mentioned  calculations  have  shown  that  both  coefficients  are  important  and significant for the fitting of Logistic Regression Model. Moreover, both variables largely influence the classification of Defaulters i.e.,  such  clients have higher tendency to  default who are unemployed and has delayed their installment over 90 days.

4. **Score the model on the test data and provide the confusion matrix for the test data using the model.** 

Below is the confusion matrix attained after scoring this model. The values are as follows: 

**True Positive (TP)   = 1782  ![](Aspose.Words.8f440b01-fbd5-4b80-882d-708c4c851d2b.022.png)![](Aspose.Words.8f440b01-fbd5-4b80-882d-708c4c851d2b.023.png)![](Aspose.Words.8f440b01-fbd5-4b80-882d-708c4c851d2b.024.png)False Positive (FP)   = 185  False Negative (FN)   = 439  True Negative (TN)   = 20321  ![](Aspose.Words.8f440b01-fbd5-4b80-882d-708c4c851d2b.009.png)**

5. **Find the accuracy, precision and recall for this algorithm on the test set.** 

**Accuracy   =**  +

- + +
- +
  - + +
- ![](Aspose.Words.8f440b01-fbd5-4b80-882d-708c4c851d2b.025.png)
- **0.9725** 

**Precision  = ![](Aspose.Words.8f440b01-fbd5-4b80-882d-708c4c851d2b.026.png)**

\+

- ![](Aspose.Words.8f440b01-fbd5-4b80-882d-708c4c851d2b.027.png)+
- ![](Aspose.Words.8f440b01-fbd5-4b80-882d-708c4c851d2b.028.png)
- **0.9059** 

**Recall   = ![](Aspose.Words.8f440b01-fbd5-4b80-882d-708c4c851d2b.029.png)**

\+

- ![](Aspose.Words.8f440b01-fbd5-4b80-882d-708c4c851d2b.030.png)+
- ![](Aspose.Words.8f440b01-fbd5-4b80-882d-708c4c851d2b.031.png)
- **0.8023 ![](Aspose.Words.8f440b01-fbd5-4b80-882d-708c4c851d2b.009.png)**

![](Aspose.Words.8f440b01-fbd5-4b80-882d-708c4c851d2b.032.png)

![](Aspose.Words.8f440b01-fbd5-4b80-882d-708c4c851d2b.033.png)

DECISION TREE - CART MODEL 

1. **Introduction**

The chapter is addressing questions related to Decision Tree Model.

2. **Which variable is the root and how many splits are there in the tree?** 

The Decision Tree has “**Job**” as root variable and there are 9 splits in the tree. ![](Aspose.Words.8f440b01-fbd5-4b80-882d-708c4c851d2b.009.png)

![](Aspose.Words.8f440b01-fbd5-4b80-882d-708c4c851d2b.034.png)

` `20  **Business Analytics Project               BBA-7B** 

![](Aspose.Words.8f440b01-fbd5-4b80-882d-708c4c851d2b.035.png)

3. **Provide the confusion matrix for the test data.** 

Below is the confusion matrix attained after scoring this model. The values are as follows: 

**True Positive (TP)   = 1683  ![](Aspose.Words.8f440b01-fbd5-4b80-882d-708c4c851d2b.036.png)![](Aspose.Words.8f440b01-fbd5-4b80-882d-708c4c851d2b.037.png)![](Aspose.Words.8f440b01-fbd5-4b80-882d-708c4c851d2b.038.png)False Positive (FP)   = 133  False Negative (FN)   = 538  True Negative (TN)   = 20373**  

4. **Find the accuracy, precision and recall for this algorithm on the test set.** 

**Accuracy   =**  +

+ + +![](Aspose.Words.8f440b01-fbd5-4b80-882d-708c4c851d2b.009.png)
- +
  - + +
- ![](Aspose.Words.8f440b01-fbd5-4b80-882d-708c4c851d2b.039.png)
- **0.9705** 

**Precision  = ![](Aspose.Words.8f440b01-fbd5-4b80-882d-708c4c851d2b.040.png)**

\+

- ![](Aspose.Words.8f440b01-fbd5-4b80-882d-708c4c851d2b.041.png)

\+

- ![](Aspose.Words.8f440b01-fbd5-4b80-882d-708c4c851d2b.042.png)
- **0.9268** 

**Recall  = ![](Aspose.Words.8f440b01-fbd5-4b80-882d-708c4c851d2b.043.png)**

\+

- ![](Aspose.Words.8f440b01-fbd5-4b80-882d-708c4c851d2b.044.png)+
- ![](Aspose.Words.8f440b01-fbd5-4b80-882d-708c4c851d2b.045.png)
- **0.7578 ![](Aspose.Words.8f440b01-fbd5-4b80-882d-708c4c851d2b.009.png)**

![](Aspose.Words.8f440b01-fbd5-4b80-882d-708c4c851d2b.046.png)

![](Aspose.Words.8f440b01-fbd5-4b80-882d-708c4c851d2b.047.png)

5. **Write all rules extracted from the decision tree.** 
1. If **Job** category is other than **unemployed** and value of **LateUpto60Days** is less than 1.5 and **lateOver90Days** is less than 0.5 and Age is greater than or equal to 63 then customer will **DEFAULT**. 
1. If **Job** category is other than **unemployed** and value of **LateUpto60Days** is less than 1.5 and **lateOver90Days** is less than 0.5 and **Age** is less than 63 then customer will **not DEFAULT.** 
1. If **Job** category is other than **unemployed** and value of **LateUpto60Days** is less than 1.5 and **lateOver90Days** is greater than or equal to 0.5 and 1.5 then customer will **DEFAULT.** 
1. If **Job** category is other than **unemployed** and value of **LateUpto60Days** is less than 1.5 and **lateOver90Days** is greater than or equal to 0.5 and less than 1.5 and his **Education** category falls in Secondary, tertiary then customer will **not DEFAULT.** 
1. If **Job** category is other than **unemployed** and value of **LateUpto60Days** is less than 1.5 and **lateOver90Days** is greater than or equal to 0.5 and less than 1.5 and his **Education** category falls in Primary, Unknown then customer will **DEFAULT.** 
1. If **Job** category is other than **unemployed** and value of **LateUpto60Days** is greater than or equal to 1.5 then customer will **DEFAULT.** ![](Aspose.Words.8f440b01-fbd5-4b80-882d-708c4c851d2b.009.png)
7. If **Job** category is **unemployed** and his **Education** category falls in Secondary, tertiary and value of **CreditBalPerc** is less than 0.68 and **Age** is greater than or equal to 39 then customer will **not** **DEFAULT.** 
7. If **Job** category is **unemployed** and his **Education** category falls in Secondary, tertiary and value of **CreditBalPerc** is less than 0.68 and **Age** is less than 39 then customer will **DEFAULT.** 
7. If **Job** category is **unemployed** and his **Education** category falls in Secondary, tertiary and value of **CreditBalPerc** is greater than or equal to 0.68 then customer will **DEFAULT.** 
7. If **Job** category is **unemployed** and his **Education** category falls in Primary, Unknown then customer will **DEFAULT.** ![](Aspose.Words.8f440b01-fbd5-4b80-882d-708c4c851d2b.009.png)

NAÏVE BAYESIAN CLASSIFICATION MODEL 

1. **Introduction**

The chapter is addressing questions related to Naïve Bayesian Classification Model.

2. **Provide the confusion matrix for the test data.** 

Below is the confusion matrix attained after scoring this model. The values are as follows: **True Positive (TP)   = 1459** 

**False Positive (FP)   = 529** 

**False Negative (FN)   = 762** 

**True Negative (TN)   = 19977** 

![](Aspose.Words.8f440b01-fbd5-4b80-882d-708c4c851d2b.048.png)

3. **Find the accuracy, precision and recall for this algorithm on the test dataset.** 

**Accuracy   =**  +

- + +
- +
  - + +
- ![](Aspose.Words.8f440b01-fbd5-4b80-882d-708c4c851d2b.049.png)
- **0.9432** 

**Precision  =  ![](Aspose.Words.8f440b01-fbd5-4b80-882d-708c4c851d2b.050.png)**

\+

- ![](Aspose.Words.8f440b01-fbd5-4b80-882d-708c4c851d2b.051.png)

\+

**= ![](Aspose.Words.8f440b01-fbd5-4b80-882d-708c4c851d2b.052.png)**

- **0.7339** 

**Recall   = ![](Aspose.Words.8f440b01-fbd5-4b80-882d-708c4c851d2b.053.png)**

\+

- ![](Aspose.Words.8f440b01-fbd5-4b80-882d-708c4c851d2b.054.png)+
- ![](Aspose.Words.8f440b01-fbd5-4b80-882d-708c4c851d2b.055.png)
- **0.6569 ![](Aspose.Words.8f440b01-fbd5-4b80-882d-708c4c851d2b.009.png)**

![](Aspose.Words.8f440b01-fbd5-4b80-882d-708c4c851d2b.056.png)

![](Aspose.Words.8f440b01-fbd5-4b80-882d-708c4c851d2b.057.png)

RANDOM FOREST MODEL 

1. **Introduction**

The chapter is addressing questions related to Random Forest Model.

2. **Score the model on the test data and provide the confusion matrix for the test data.** 

Below is the confusion matrix attained after scoring this model. The values are as follows: **True Positive (TP)   = 1818** 

**False Positive (FP)   = 139** 

**False Negative (FN)   = 403** 

**True Negative (TN)   = 20367** 

![](Aspose.Words.8f440b01-fbd5-4b80-882d-708c4c851d2b.058.png)

3. **Find the accuracy, precision and recall for this algorithm on the test set.** 

**Accuracy   =**   +

- + +
- +
  - + +
- ![](Aspose.Words.8f440b01-fbd5-4b80-882d-708c4c851d2b.059.png)
- **0.9764** 

**Precision  =   ![](Aspose.Words.8f440b01-fbd5-4b80-882d-708c4c851d2b.060.png)**

\+

- ![](Aspose.Words.8f440b01-fbd5-4b80-882d-708c4c851d2b.061.png)

+![](Aspose.Words.8f440b01-fbd5-4b80-882d-708c4c851d2b.009.png)

- ![](Aspose.Words.8f440b01-fbd5-4b80-882d-708c4c851d2b.062.png)
- **0.9314** 

**Recall   =  ![](Aspose.Words.8f440b01-fbd5-4b80-882d-708c4c851d2b.063.png)**

\+

- ![](Aspose.Words.8f440b01-fbd5-4b80-882d-708c4c851d2b.064.png)+
- ![](Aspose.Words.8f440b01-fbd5-4b80-882d-708c4c851d2b.065.png)
- **0.8186 ![](Aspose.Words.8f440b01-fbd5-4b80-882d-708c4c851d2b.009.png)**

![](Aspose.Words.8f440b01-fbd5-4b80-882d-708c4c851d2b.066.png)

![](Aspose.Words.8f440b01-fbd5-4b80-882d-708c4c851d2b.067.png)

K NEAREST NEIGHBOR MODEL 

1. **Introduction**

The chapter is addressing questions related to K Nearest Neighbors.

2. **Pre-Requisite Step** 

We switched to variables window and then converted the Data Class of Job, Status and Education variable to “Numeric” by using “Make Numeric” option. 

3. **Provide the confusion matrix for the test data.** 

**For K = 35:** Below is the confusion matrix attained after scoring this model. The values are as follows: 

- **True Positive (TP)   = 250** 
- **False Positive (FP)   = 99** 
- **False Negative (FN)   = 1556** 
- **True Negative (TN)   = 17033** 

![](Aspose.Words.8f440b01-fbd5-4b80-882d-708c4c851d2b.068.png)

**For K = 75:** Below is the confusion matrix attained after scoring this model. The values are as follows: 

- **True Positive (TP)   = 204** 
- **False Positive (FP)   = 101** 
- **False Negative (FN)   = 1602** 
- **True Negative (TN)   = 17031 ![](Aspose.Words.8f440b01-fbd5-4b80-882d-708c4c851d2b.009.png)**

` `32  

![](Aspose.Words.8f440b01-fbd5-4b80-882d-708c4c851d2b.069.png)

**For K = 125:** Below is the confusion matrix attained after scoring this model. The values are as follows: 

- **True Positive (TP)   = 180** 
- **False Positive (FP)   = 96** 
- **False Negative (FN)   = 1626** 
- **True Negative (TN)   = 17036** 

![](Aspose.Words.8f440b01-fbd5-4b80-882d-708c4c851d2b.070.png)

4. **Find the accuracy, precision and recall for this algorithm on the test set.** 

**For K = 35** 

**Accuracy   =**  +

- + +
- +
  - + +
- ![](Aspose.Words.8f440b01-fbd5-4b80-882d-708c4c851d2b.071.png)
- **0.9126 ![](Aspose.Words.8f440b01-fbd5-4b80-882d-708c4c851d2b.009.png)**

**Precision  =  ![](Aspose.Words.8f440b01-fbd5-4b80-882d-708c4c851d2b.072.png)**

\+

- ![](Aspose.Words.8f440b01-fbd5-4b80-882d-708c4c851d2b.073.png)

\+

- ![](Aspose.Words.8f440b01-fbd5-4b80-882d-708c4c851d2b.074.png)
- **0.7163** 

**Recall  =   ![](Aspose.Words.8f440b01-fbd5-4b80-882d-708c4c851d2b.075.png)**

\+

- ![](Aspose.Words.8f440b01-fbd5-4b80-882d-708c4c851d2b.076.png)+
- ![](Aspose.Words.8f440b01-fbd5-4b80-882d-708c4c851d2b.077.png)
- **0.1384** 

![](Aspose.Words.8f440b01-fbd5-4b80-882d-708c4c851d2b.078.png)

**For K = 75** 

**Accuracy   =**  +

- + +
- +
  - + +![](Aspose.Words.8f440b01-fbd5-4b80-882d-708c4c851d2b.009.png)
- ![](Aspose.Words.8f440b01-fbd5-4b80-882d-708c4c851d2b.079.png)
- **0.9101** 

**Precision  =  ![](Aspose.Words.8f440b01-fbd5-4b80-882d-708c4c851d2b.080.png)**

\+

- ![](Aspose.Words.8f440b01-fbd5-4b80-882d-708c4c851d2b.081.png)+
- ![](Aspose.Words.8f440b01-fbd5-4b80-882d-708c4c851d2b.082.png)
- **0.6689** 

**Recall  = ![](Aspose.Words.8f440b01-fbd5-4b80-882d-708c4c851d2b.083.png)**

\+

- ![](Aspose.Words.8f440b01-fbd5-4b80-882d-708c4c851d2b.084.png)+
- ![](Aspose.Words.8f440b01-fbd5-4b80-882d-708c4c851d2b.085.png)
- **0.1130** 

![](Aspose.Words.8f440b01-fbd5-4b80-882d-708c4c851d2b.086.png)

**For K = 125** 

**Accuracy   =**  +

+ + +![](Aspose.Words.8f440b01-fbd5-4b80-882d-708c4c851d2b.009.png)
- +
  - + +
- ![](Aspose.Words.8f440b01-fbd5-4b80-882d-708c4c851d2b.087.png)
- **0.9091** 

**Precision  = ![](Aspose.Words.8f440b01-fbd5-4b80-882d-708c4c851d2b.088.png)**

\+

- ![](Aspose.Words.8f440b01-fbd5-4b80-882d-708c4c851d2b.089.png)

\+

- ![](Aspose.Words.8f440b01-fbd5-4b80-882d-708c4c851d2b.090.png)
- **0.6522** 

**Recall  = ![](Aspose.Words.8f440b01-fbd5-4b80-882d-708c4c851d2b.091.png)**

\+

- ![](Aspose.Words.8f440b01-fbd5-4b80-882d-708c4c851d2b.051.png)

\+

- ![](Aspose.Words.8f440b01-fbd5-4b80-882d-708c4c851d2b.045.png)
- **0.0997 ![](Aspose.Words.8f440b01-fbd5-4b80-882d-708c4c851d2b.009.png)**

![](Aspose.Words.8f440b01-fbd5-4b80-882d-708c4c851d2b.092.png)

5. **Which value of K among these provides the maximum accuracy.** 

Maximum accuracy (i.e., **0.9126 or 91.26%**) is attained when value of **K = 35.** According to the results when we increase the number of neighbors, the accuracy starts decreasing.** 

6. **Compare all model evaluation metrics (accuracy etc.) obtained by the five algorithms by making a comparison table and comment on the findings.** 

**Table 1: Comparison of all Model Evaluation Metrics** 



|**Model Name** |**Accuracy (%)** |**Precision** |**Recall** |**Balanced Accuracy** |
| - | - | - | - | - |
|**Logistic Regression** |0.9725 |0.9059 |0.8023 |0.8967 |
|**Decision Tree** |0.9705 |0.9268 |0.7578 |0.8756 |
|**Naïve Bayesian Classification** |0.9432 |0.7339 |0.6569 |0.8156 |
|**Random Forest** |0.9762 |0.9314 |0.8186 |0.9060 |
|**K Nearest Neighbor** |**35** |0.9126 |0.7163 |0.1384 |0.5663 |
||**75** |0.9101 |0.6689 |0.1130 |0.547 |
||**125** |0.9091 |0.6522 |0.0997 |0.547 |
**Findings mined from Comparison:** 

Following are the findings after  comparing all model evaluation metrics obtained by the five models: 

- Our dataset is skewed, majority class encompasses non-defaulters (0), and minority class covers  defaulters  (1).  Skewness  creates  class  imbalancing  problem  while  training classification models and model prediction will always be biased towards majority class. 
- **Remedial Measures**: Following remedies can be applied to overcome this problem: 

▪  we need to balance both classes first and assign weights to both classes to get good results. 

- Best model is **Random Forest** for the given problem i.e., Loan Defaulter Classification as it gives maximum classification accuracy, maximum kappa score and maximum balanced accuracy. Random Forest handles class imbalancing problems itself.  
- Dimensions of our dataset is smaller, so **Decision Tree** and **Logistic Regression** can also be used for this type of datasets but handling class imbalancing is necessary to reduce the biasness. 
- **Naïve  Bayes  classifier**  performs  well  in  situations  when  features  are  conditionally independent but when features are dependent, its performance goes down. In our case we have features that are dependent like jobs type and salary are dependent, job type and open loans are dependent, education and job are dependent etc. 
- **K-Nearest Neighbor** is not a very good classifiers for this type of datasets as it measures the distance from the neighbors and when we increase the number of neighbors the probability of occurrence of test samples tends to increase towards majority class. We can see in above table that all of the KNN models has shown worst balanced accuracy. Balanced accuracy is a metric that one can use when evaluating how good a binary classifier is. It is especially useful when the classes are imbalanced, i.e., one of the two classes appears a lot more often than the other. ![](Aspose.Words.8f440b01-fbd5-4b80-882d-708c4c851d2b.009.png)
- **K-fold  Cross  Validation**  is  a  good  approach  to  improve  classifiers  as  it  validates  the predictions with all folds of data. It improved accuracy as well as Kappa Score of our models as shown in table below. Kappa score is a quantitative measure of reliability of the dataset. 

**Table 2: Comparison of Models before and after K-Fold Cross Validation ![](Aspose.Words.8f440b01-fbd5-4b80-882d-708c4c851d2b.009.png)**



|**Models** |**Accuracy  (Without K-fold)** |**Accuracy (With 5- fold)** |**Difference** |**Kappa Score  (Without K-fold)*** |**Kappa Score  (With K-fold)*** |**Difference** |
| - | - | :- | - | :- | :- | - |
|**Random Forest** |0.9762 |**0.9889** |0.0217 |0.8584* |0.9219* |**0.0635** |
|**Decision Tree:** |0.9705 |` `**0.9789**  |0.0084 |0.8178* |0.8709* |**0.0531** |
|**Logistic Regression** |0.9725 |**0.9740** |0.0015 |0.8359* |0.8398* |**0.0039** |
|**Naïve Bayes** |0.9432 |` `**0.9490**  |0.0058 |0.6621* |0.6313* |**-0.0308** |
|**KNN** |0.9127 |**0.9313** |0.0186 |0.2075* |0.4555* |**0.2480** |
CLASSIFYING UNKNOWN DATA 

**8.1  Question**

The bank’s CEO has provided you with some data from pending loan applications. This data is given on the last page. He wants to know who among these ten clients are likely to default if their loan is approved. Using only your ‘Logistic Regression model’, make predictions for the missing target variable ‘Default’ based upon provided attribute values for each case. Prepare your response for the CEO accordingly. 

**Answer:  ![](Aspose.Words.8f440b01-fbd5-4b80-882d-708c4c851d2b.009.png)**

![](Aspose.Words.8f440b01-fbd5-4b80-882d-708c4c851d2b.093.png)

![](Aspose.Words.8f440b01-fbd5-4b80-882d-708c4c851d2b.094.png)

**Table 3: Comparison of Predictions for given Test Dataset** 



|**Case No.** |**Logistic Regression** |**Decision Tree** |**Naïve Bayes** |**Random Forest** |**KNN** |
| - | :- | - | - | :-: | - |
|**35D** |0 |0 |0 |0 |0 |
|**21W** |0 |0 |0 |0 |0 |
|**42T** |0 |0 |0 |0 |0 |
|**65Y** |0 |0 |0 |0 |0 |
|**69P** |0 |0 |0 |0 |0 |
|**58K** |0 |0 |0 |0 |0 |
|**32A** |0 |0 |0 |0 |0 |
|**76B** |1 |1 |1 |1 |0 |
|**71C** |0 |0 |0 |0 |0 |
|**12N** |1 |1 |0 |1 |0 |
**Response To CEO:**  After  predicting the  defaulters  using  Logistic  Regression  model,  it  is revealed that case no. **76B** and **12N** are defaulters. Moreover, Random Forest and Decision Tree 

depicted the same result. Naïve Bayesian failed to detect 12N whereas KNN has shown worst performance and failed to detect any. ![](Aspose.Words.8f440b01-fbd5-4b80-882d-708c4c851d2b.009.png)

RECOMMENDATIONS TO CEO 

1. **Question**

Write a concluding paragraph and provide a set of recommendations to the CEO  based upon your entire analysis to enable him to gain insight into his loan approval process so that the bank reduces loan  defaulters.  The  CEO  is  particularly  interested  in  particular  customer  attributes  and characteristics leading to default, so you must focus on those too. You may also use any other method or technique not covered in class to answer this part to get extra credit. 

2. **Conclusion** 

The major task was to classify loan applications as a loan approval or a loan denial. But before applying any model to our dataset, we did some preprocessing steps because preprocessing the data not only helps us smooth out inconsistencies but also gives us a comprehensive understanding of the data which in turn aids us in our model selection process. Pre-requisite steps include conversion  of  data  class  of  various  variables. We  applied  different  algorithms  and  found  out “**Random Forest**” as best model for given problem. On basis of these techniques, we tested and then provided some recommendations to the CEO so that the bank reduces loan defaulters. 

3. **Recommendations** 

After analysis of all the given methods, we concluded that “**Random Forest**” outperformed all of the other models with an accuracy of **97.62%** and **98.89%,** before and after K-Fold Cross Validation respectively.  Moreover,  we  have  mined  multiple  thoughts  and  came  up  with  following recommendations so that the bank reduces loan defaulters. Which are as follows:

- The bank shouldn’t approve loan for those clients who are “**Unemployed**”. 
- Also,  the  bank  should  prefer  not  to  give  loan  with  age  greater  than  63  or  have  less education. Mean if they fall in education category under primary or unknown. 
- Customers between 39 and 63 are suitable to give loan. 
- The important variables to emphasize or enhance while processing loan application are **Job, Age, Income and Education**. So, CEO should be more concerned with Socio-Demographic Information.  
- Multiple  models  have  shown  significant  variables,  so  CEO  should  gather  enhanced information  related  to  these  variables.  Emphasizing  more  on  these  variables  will  also improves the model accuracy. 
- Unimportant features or variables (i.e., have p-value greater than 0.05) should be pruned or removed from the dataset. By doing so, we can lessen the computation cost and in return can improve the model’s accuracy. ![](Aspose.Words.8f440b01-fbd5-4b80-882d-708c4c851d2b.009.png)
4. **Supplementary Method** 

To Improve the accuracy and resolve the imbalancing problem, we tried another model named as “**XGBoost**”. It is a decision-tree-based ensemble Machine Learning algorithm that uses a gradient boosting framework. As per the visualization and statistics of features importance of XGBoost model, it can be seen that “job” is the attribute/feature which has maximum information gain as compare to rest of the features. Because of having maximum information gain, Job features is being used as root node of the tree in Decision tree classifier.

![](Aspose.Words.8f440b01-fbd5-4b80-882d-708c4c851d2b.095.png)

![](Aspose.Words.8f440b01-fbd5-4b80-882d-708c4c851d2b.096.png)According to the confusion matrix shown below, accuracy of XGBoost is **97.66%** and kappa score (reliability) is 0.8577. Precision of model is 0.9525, Recall is 0.8013 and F1-Score is 0.8704. Whole statistics tells that the model performance of XGBoost outperformed all other models. 

![](Aspose.Words.8f440b01-fbd5-4b80-882d-708c4c851d2b.097.png) ![](Aspose.Words.8f440b01-fbd5-4b80-882d-708c4c851d2b.098.png)

5. **Final Thoughts on New Method** 

We can see from the above-mentioned statistics, XGBoost has shown accuracy of **97.66%** without any Model Tunning i.e., K-Fold Cross Validation. So, we recommend usage of this model to the CEO. By utilizing this method, we can predict and reduce large numbers loan defaulters. ![](Aspose.Words.8f440b01-fbd5-4b80-882d-708c4c851d2b.009.png)
` `44  

**Business Analytics Project               BBA-7B** 
