# Exploratory Data Analysis of banking variables for a Private Financial firm.
A comprehensive dataset for analyzing loan-related data using Python. Includes information on loan amounts, interest rates, borrower demographics, and repayment status. Ideal for exploring statistical patterns, risk assessment, and building predictive models in financial analytics.Develops banking variables for financial analysis. Utilizes Python to create robust tools for transaction analysis, risk assessment, and customer profiling. Enhances decision-making processes through comprehensive data insights, improving financial strategies and performance."

## Importing the main Libraries and Data

![image](https://github.com/Himanshu2112000/Python_Or_Data_Analysis/assets/164239242/6cd61665-5cb6-48e1-b4db-9be4bba2c0e4)

**There are 2500 records for 15 variables.**

#Databases Used:
- ['LoanID', 'Amount.Requested', 'Amount.Funded.By.Investors',
       'Interest.Rate', 'Loan.Length', 'Loan.Purpose', 'Debt.To.Income.Ratio',
       'State', 'Home.Ownership', 'Monthly.Income', 'FICO.Range',
       'Open.CREDIT.Lines', 'Revolving.CREDIT.Balance',
       'Inquiries.in.the.Last.6.Months', 'Employment.Length'],

 ## These columns are essential for Python-based data analysis in finance. They encompass crucial loan parameters such as requested and funded amounts, interest rates, loan length, purpose, borrower demographics, credit history, and employment details. Through Python, comprehensive analysis enables informed decision-making and risk assessment in financial lending processes.

## EDA: Exploratory Data Analysis
### Step1: Variables names following the Naming Convention,

![image](https://github.com/Himanshu2112000/Python_Or_Data_Analysis/assets/164239242/0409ce1e-12c7-4874-8c20-10ed5aa4e3f4)

![image](https://github.com/Himanshu2112000/Python_Or_Data_Analysis/assets/164239242/3954852a-ae80-470a-bb47-5c8b94afe74a)

![image](https://github.com/Himanshu2112000/Python_Or_Data_Analysis/assets/164239242/ea071ecd-2f79-4b67-b995-c92f16e248b4)

### Step 2: Check the information: Data type Conversions

![image](https://github.com/Himanshu2112000/Python_Or_Data_Analysis/assets/164239242/1c8c3c52-3efa-4f3c-adad-a87dc9364a02)

![image](https://github.com/Himanshu2112000/Python_Or_Data_Analysis/assets/164239242/8bb3e612-26e0-4e25-8a79-f5b3ad130e31)

![image](https://github.com/Himanshu2112000/Python_Or_Data_Analysis/assets/164239242/e37f2db6-370a-4c22-8b2c-0d0dcf739548)

![image](https://github.com/Himanshu2112000/Python_Or_Data_Analysis/assets/164239242/83cac5fc-8d3c-4105-8d47-39cc5bb5a442)

## Data type conversions:

![image](https://github.com/Himanshu2112000/Python_Or_Data_Analysis/assets/164239242/9f976d0c-f8f9-4ad2-b12b-1a712284906c)

![image](https://github.com/Himanshu2112000/Python_Or_Data_Analysis/assets/164239242/e8648b90-0233-4cc0-a5c7-295eb8ada881)

## Checking the relevant and irrelevant variables in the first phase of EDA:

![image](https://github.com/Himanshu2112000/Python_Or_Data_Analysis/assets/164239242/7fa348df-0042-4e73-a6b0-fc7b16c7d756)

![image](https://github.com/Himanshu2112000/Python_Or_Data_Analysis/assets/164239242/1670b622-1a81-4d54-a8d1-9ee4c7704552)

![image](https://github.com/Himanshu2112000/Python_Or_Data_Analysis/assets/164239242/a295814b-0109-4879-9c63-6d4db752adfd)

## Distribution of customers by State:

![image](https://github.com/Himanshu2112000/Python_Or_Data_Analysis/assets/164239242/8ff3b7d4-be38-418d-a673-e31be68f0432)

![image](https://github.com/Himanshu2112000/Python_Or_Data_Analysis/assets/164239242/4eb98d23-e6a8-4711-a2df-df488b3499f2)

![image](https://github.com/Himanshu2112000/Python_Or_Data_Analysis/assets/164239242/280a0c05-1da5-485f-a57b-f94af35128d9)

![image](https://github.com/Himanshu2112000/Python_Or_Data_Analysis/assets/164239242/ae581209-1978-4379-a0a1-f2590cca9f2a)

![image](https://github.com/Himanshu2112000/Python_Or_Data_Analysis/assets/164239242/00426c12-b453-481d-a683-b5396aa2c679)

## Data Duplicacy: Chech if their is duplicate data or not: DDT ( Data Duplicacy Treatment)

![image](https://github.com/Himanshu2112000/Python_Or_Data_Analysis/assets/164239242/e5fe9a96-c845-41be-8575-0c556a254e53)

## Missing Values Treatment:

![image](https://github.com/Himanshu2112000/Python_Or_Data_Analysis/assets/164239242/7adb910b-df0c-406e-a71d-f4812c9f0619)

## Creating a UDF which can automate the missing value treatment.

![image](https://github.com/Himanshu2112000/Python_Or_Data_Analysis/assets/164239242/503964b9-3bf9-4174-a0ac-825d53d008a7)

![image](https://github.com/Himanshu2112000/Python_Or_Data_Analysis/assets/164239242/861e2c0c-f420-465f-9507-513d7300cec2)


## Separating the categorical Variables and Numerical variables into two different datasets for Data Preparations for Data Analysis.

![image](https://github.com/Himanshu2112000/Python_Or_Data_Analysis/assets/164239242/b17e4172-38fe-4a3a-af76-30a7e63a2fb8)

## Filling missing values in Numerical data with the Median values.

![image](https://github.com/Himanshu2112000/Python_Or_Data_Analysis/assets/164239242/45426800-0e0f-4b68-bc24-40153011a0e6)

# Filling missing values in Categorical data with the Mode values.

![image](https://github.com/Himanshu2112000/Python_Or_Data_Analysis/assets/164239242/b3c4fe21-305e-4d1f-8924-7ce2cd3885ba)

![image](https://github.com/Himanshu2112000/Python_Or_Data_Analysis/assets/164239242/6efc769e-7e86-4ccc-acc9-e7c614efc93c)

![image](https://github.com/Himanshu2112000/Python_Or_Data_Analysis/assets/164239242/854ceee2-536c-43e6-ac6d-465c0ba8a948)

![image](https://github.com/Himanshu2112000/Python_Or_Data_Analysis/assets/164239242/98b4f980-99a1-4cf7-b85a-e5adb538fba0)

## Outlier Treatment

![image](https://github.com/Himanshu2112000/Python_Or_Data_Analysis/assets/164239242/1d56a44b-7e02-4bcf-8b7a-d262d9273f8d)

### Just observing a single column for the outliers

![image](https://github.com/Himanshu2112000/Python_Or_Data_Analysis/assets/164239242/8544d8c6-63fa-4c97-8e64-b65c795f5820)

## quantile() helps to find the percentile vaues at each percentile mark.

![image](https://github.com/Himanshu2112000/Python_Or_Data_Analysis/assets/164239242/3f97bb65-b594-489c-a8db-2e07c7529c2e)

![image](https://github.com/Himanshu2112000/Python_Or_Data_Analysis/assets/164239242/c13ff971-6b42-4c20-af22-3446ba216f6c)

![image](https://github.com/Himanshu2112000/Python_Or_Data_Analysis/assets/164239242/ec80bd5c-c76a-4e2e-9307-bc7e602970cc)

![image](https://github.com/Himanshu2112000/Python_Or_Data_Analysis/assets/164239242/345f8340-0d9e-4707-90c8-70d9e558261e)

![image](https://github.com/Himanshu2112000/Python_Or_Data_Analysis/assets/164239242/5c83480b-7742-4813-892d-864d36048f1a)

![image](https://github.com/Himanshu2112000/Python_Or_Data_Analysis/assets/164239242/00713b41-6484-44db-ad98-593ccaa95f29)

## Outlier treatment IQR Method

![image](https://github.com/Himanshu2112000/Python_Or_Data_Analysis/assets/164239242/844ffe66-0ce4-46f1-92dc-d75eb4f7e547)

![image](https://github.com/Himanshu2112000/Python_Or_Data_Analysis/assets/164239242/037845fa-c2a4-4915-b884-90f8c87baac1)

## Outlier treatment of only required columns,

![image](https://github.com/Himanshu2112000/Python_Or_Data_Analysis/assets/164239242/5bd71ffe-cec8-48f7-9b21-8f9d59cd05c5)

![image](https://github.com/Himanshu2112000/Python_Or_Data_Analysis/assets/164239242/c635dc70-402f-45cd-b351-3181df2a3387)

![image](https://github.com/Himanshu2112000/Python_Or_Data_Analysis/assets/164239242/800b5d39-0a8d-48b9-9a57-2ff76eb0d740)

![image](https://github.com/Himanshu2112000/Python_Or_Data_Analysis/assets/164239242/4ab310eb-b4d3-46d4-a226-7d538cb2d465)

![image](https://github.com/Himanshu2112000/Python_Or_Data_Analysis/assets/164239242/717b275e-8398-4405-9ba9-83182a4cc2dc)

![image](https://github.com/Himanshu2112000/Python_Or_Data_Analysis/assets/164239242/c0d672c3-cb5c-4d38-9a98-9621c14ab80d)

![image](https://github.com/Himanshu2112000/Python_Or_Data_Analysis/assets/164239242/8900e316-c262-4f8b-b900-9896eda61e11)

## Outlier treatment on all columns in num_data_2b

![image](https://github.com/Himanshu2112000/Python_Or_Data_Analysis/assets/164239242/30abfe6c-a374-4150-8471-02656501b6bb)

![image](https://github.com/Himanshu2112000/Python_Or_Data_Analysis/assets/164239242/49bd858d-687b-45e1-863e-be5e174ad911)

![image](https://github.com/Himanshu2112000/Python_Or_Data_Analysis/assets/164239242/bc793423-0e2e-42f3-9bce-81e7fc7ec554)

## Merging the categorical and the numerical data to get the dataset

![image](https://github.com/Himanshu2112000/Python_Or_Data_Analysis/assets/164239242/5e023eca-8d0a-4233-9713-6e971b314ec0)

## One-Hot Encoding: Conversion of categorical variables to continuous variables.

![image](https://github.com/Himanshu2112000/Python_Or_Data_Analysis/assets/164239242/9ae9d84c-0c09-44e7-b321-7ace81c0117a)

![image](https://github.com/Himanshu2112000/Python_Or_Data_Analysis/assets/164239242/ef1b8696-4dd9-49f6-8e23-b72e3ccfc931)

![image](https://github.com/Himanshu2112000/Python_Or_Data_Analysis/assets/164239242/455b55c0-4351-4992-843c-90be0bb5a189)

## Logarithmic Transformations

![image](https://github.com/Himanshu2112000/Python_Or_Data_Analysis/assets/164239242/2fba9bbb-3d85-4487-a45e-044b282a61fa)

**Check all the variables distribution after logarithmic transformation.**

![image](https://github.com/Himanshu2112000/Python_Or_Data_Analysis/assets/164239242/b5bbceb8-ac53-4de1-8f48-9b82be95e41b)



## Standardisation of the numerical data

![image](https://github.com/Himanshu2112000/Python_Or_Data_Analysis/assets/164239242/aa000232-9154-477b-bee8-fd6fac21f58d)

![image](https://github.com/Himanshu2112000/Python_Or_Data_Analysis/assets/164239242/09d443f5-d230-4fb9-a84b-2dba87f8d5cf)

# Feature Engineering Analysis

![image](https://github.com/Himanshu2112000/Python_Or_Data_Analysis/assets/164239242/06d3c37b-f2c3-417b-ade3-4076d35a1933)

![image](https://github.com/Himanshu2112000/Python_Or_Data_Analysis/assets/164239242/78f3a93c-bfe4-410b-a723-f8336ca49d52)

![image](https://github.com/Himanshu2112000/Python_Or_Data_Analysis/assets/164239242/7a57be39-e636-4e6c-8f4a-39f01b94ca8c)

##  VIF ANALYSIS: Checking the multicollinearity within the independent variables.

![image](https://github.com/Himanshu2112000/Python_Or_Data_Analysis/assets/164239242/b0eb53c9-3ab6-477f-8a8f-528639292e9c)

## Forward Selection and Backward Elimination Technique

![image](https://github.com/Himanshu2112000/Python_Or_Data_Analysis/assets/164239242/38d66c79-48d7-447e-8cfc-733e30708a0c)

## Splitting of the data into Training and Testing dataset: (70% training data, 30% testing data)

![image](https://github.com/Himanshu2112000/Python_Or_Data_Analysis/assets/164239242/33f8208d-f402-4b86-9c98-081b6ca4b661)

## Splitting The datasets into train and test

![image](https://github.com/Himanshu2112000/Python_Or_Data_Analysis/assets/164239242/a1ff35a3-1d50-453a-bf0d-7c9d613154e4)

##  Model Building: OLS Regression

![image](https://github.com/Himanshu2112000/Python_Or_Data_Analysis/assets/164239242/fa63fc8d-929b-4f26-808e-9f24a1988f2a)

![image](https://github.com/Himanshu2112000/Python_Or_Data_Analysis/assets/164239242/d084ed99-d122-47bf-875d-0a83813eb879)






























































