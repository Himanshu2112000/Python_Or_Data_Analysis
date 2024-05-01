# Exploratory Data Analysis of banking variables for a Private Financial firm.
A comprehensive dataset for analyzing loan-related data using Python. Includes information on loan amounts, interest rates, borrower demographics, and repayment status. Ideal for exploring statistical patterns, risk assessment, and building predictive models in financial analytics.Develops banking variables for financial analysis. Utilizes Python to create robust tools for transaction analysis, risk assessment, and customer profiling. Enhances decision-making processes through comprehensive data insights, improving financial strategies and performance."

## Importing the main Libraries and Data

![image](https://github.com/Himanshu2112000/Python_Or_Data_Analysis/assets/164239242/6cd61665-5cb6-48e1-b4db-9be4bba2c0e4)

**There are 2500 records for 15 variables.**

## Databases Used:
- ['LoanID', 'Amount.Requested', 'Amount.Funded.By.Investors',
       'Interest.Rate', 'Loan.Length', 'Loan.Purpose', 'Debt.To.Income.Ratio',
       'State', 'Home.Ownership', 'Monthly.Income', 'FICO.Range',
       'Open.CREDIT.Lines', 'Revolving.CREDIT.Balance',
       'Inquiries.in.the.Last.6.Months', 'Employment.Length'],

### These columns are essential for Python-based data analysis in finance. They encompass crucial loan parameters such as requested and funded amounts, interest rates, loan length, purpose, borrower demographics, credit history, and employment details. Through Python, comprehensive analysis enables informed decision-making and risk assessment in financial lending processes.


## EDA: Exploratory Data Analysis

### Conducting Exploratory Data Analysis (EDA) on the dataset to prepare it for effective data analysis. This process involves understanding data distributions, identifying patterns, handling missing values, outliers, and ensuring data quality. By cleaning, transforming, and visualizing data, EDA enhances its usability and enables meaningful insights for further analysis."

### Step1: Variables names following the Naming Convention,

![image](https://github.com/Himanshu2112000/Python_Or_Data_Analysis/assets/164239242/0409ce1e-12c7-4874-8c20-10ed5aa4e3f4)

![image](https://github.com/Himanshu2112000/Python_Or_Data_Analysis/assets/164239242/3954852a-ae80-470a-bb47-5c8b94afe74a)

![image](https://github.com/Himanshu2112000/Python_Or_Data_Analysis/assets/164239242/ea071ecd-2f79-4b67-b995-c92f16e248b4)

## Performing naming conventions on a dataset is crucial for enhancing its clarity and usability in data analysis tasks. This process involves standardizing the case style, removing special characters, shortening lengthy names, and ensuring consistency across all variables or columns. Descriptive names that clearly convey the content or meaning of each variable are preferred, avoiding conflicts with reserved words. Documentation of the naming conventions used facilitates future reference, maintaining the dataset's clarity and ease of use


### Step 2: Check the information: Data type Conversions

![image](https://github.com/Himanshu2112000/Python_Or_Data_Analysis/assets/164239242/1c8c3c52-3efa-4f3c-adad-a87dc9364a02)

![image](https://github.com/Himanshu2112000/Python_Or_Data_Analysis/assets/164239242/8bb3e612-26e0-4e25-8a79-f5b3ad130e31)

![image](https://github.com/Himanshu2112000/Python_Or_Data_Analysis/assets/164239242/e37f2db6-370a-4c22-8b2c-0d0dcf739548)

![image](https://github.com/Himanshu2112000/Python_Or_Data_Analysis/assets/164239242/83cac5fc-8d3c-4105-8d47-39cc5bb5a442)

## Data type conversions:

![image](https://github.com/Himanshu2112000/Python_Or_Data_Analysis/assets/164239242/9f976d0c-f8f9-4ad2-b12b-1a712284906c)

![image](https://github.com/Himanshu2112000/Python_Or_Data_Analysis/assets/164239242/e8648b90-0233-4cc0-a5c7-295eb8ada881)

## Performing data conversion to align with required analysis involves transforming raw data into a format suitable for the analytical techniques and methods planned for the project. This may include converting data types, aggregating or disaggregating data, standardizing units of measurement, and handling missing or erroneous values. By tailoring the data to meet the specific requirements of the analysis, it becomes more conducive to deriving meaningful insights and drawing accurate conclusions

## Checking the relevant and irrelevant variables in the first phase of EDA:

![image](https://github.com/Himanshu2112000/Python_Or_Data_Analysis/assets/164239242/7fa348df-0042-4e73-a6b0-fc7b16c7d756)

![image](https://github.com/Himanshu2112000/Python_Or_Data_Analysis/assets/164239242/1670b622-1a81-4d54-a8d1-9ee4c7704552)

![image](https://github.com/Himanshu2112000/Python_Or_Data_Analysis/assets/164239242/a295814b-0109-4879-9c63-6d4db752adfd)

## Distribution of customers by State:

![image](https://github.com/Himanshu2112000/Python_Or_Data_Analysis/assets/164239242/8ff3b7d4-be38-418d-a673-e31be68f0432)

![image](https://github.com/Himanshu2112000/Python_Or_Data_Analysis/assets/164239242/4eb98d23-e6a8-4711-a2df-df488b3499f2)

### This code snippet prints the value counts of the 'State' column in the dataset and visualizes the distribution of customers by state using a bar plot. The printed counts provide insights into the frequency of occurrence of each state in the dataset, while the bar plot offers a graphical representation of this distribution, facilitating easier interpretation and analysis.


![image](https://github.com/Himanshu2112000/Python_Or_Data_Analysis/assets/164239242/280a0c05-1da5-485f-a57b-f94af35128d9)

![image](https://github.com/Himanshu2112000/Python_Or_Data_Analysis/assets/164239242/ae581209-1978-4379-a0a1-f2590cca9f2a)

### This code snippet calculates the value counts of the 'Loan_Purpose' column in the dataset, providing insights into the frequency of each loan purpose. Subsequently, it visualizes the distribution of customers by their loan purpose using a bar plot, where each bar represents the number of customers associated with a specific loan purpose. The plot aids in understanding the distribution pattern and identifying predominant loan purposes among customers. The code employs the matplotlib library for plotting, setting appropriate labels for clarity, and ensures readability by specifying the figure size.


![image](https://github.com/Himanshu2112000/Python_Or_Data_Analysis/assets/164239242/00426c12-b453-481d-a683-b5396aa2c679)

### This code segment prints the value counts of the 'Home_Ownership' column in the dataset, revealing the frequency of each home ownership category among customers. It then generates a bar plot to visualize this distribution, providing insights into the distribution pattern and predominant types of home ownership among customers. The matplotlib library is utilized for plotting, and appropriate labels are set for clarity, while the figure size is specified for readability.

## Data Duplicacy: Chech if their is duplicate data or not: DDT ( Data Duplicacy Treatment)

![image](https://github.com/Himanshu2112000/Python_Or_Data_Analysis/assets/164239242/e5fe9a96-c845-41be-8575-0c556a254e53)

### Performing data deduplication involves identifying and removing duplicate records within a dataset. This process ensures data integrity and accuracy by eliminating redundant information. Using Python's pandas library, duplicate rows are detected and removed based on specified columns. The resulting dataset contains only unique records, optimizing data quality for subsequent analysis. By comparing the shape of the original and deduplicated data, insights into the extent of duplication can be gained, facilitating further data refinement and analysis.


## Missing Values Treatment:

![image](https://github.com/Himanshu2112000/Python_Or_Data_Analysis/assets/164239242/7adb910b-df0c-406e-a71d-f4812c9f0619)

### Performing missing values treatment is a crucial step in data preprocessing, essential for ensuring the integrity and reliability of subsequent analyses. This process involves identifying missing values within the dataset using pandas functions like isnull() or info(), followed by determining the most appropriate method for handling them. Imputation techniques, such as replacing missing values with mean, median, or mode, offer a common approach, while deletion strategies involve removing rows or columns with missing data. Validation of the treatment's effectiveness is vital, typically achieved by rechecking for missing values post-treatment. Documenting the entire process enhances transparency and reproducibility, facilitating robust data analysis and interpretation.

## Creating a UDF which can automate the missing value treatment.

![image](https://github.com/Himanshu2112000/Python_Or_Data_Analysis/assets/164239242/503964b9-3bf9-4174-a0ac-825d53d008a7)

![image](https://github.com/Himanshu2112000/Python_Or_Data_Analysis/assets/164239242/861e2c0c-f420-465f-9507-513d7300cec2)

### The miss_value_treat function is a user-defined function (UDF) designed to treat missing values in a pandas Series object s. This function employs conditional logic to differentiate between object (categorical) and non-object (numerical) data types within the Series. For object type data, missing values are imputed with the mode (most frequent value), while for numerical data, missing values are filled with the median. The function provides a versatile and automated approach to handle missing data effectively, enhancing data integrity and enabling seamless analysis.


## Separating the categorical Variables and Numerical variables into two different datasets for Data Preparations for Data Analysis.

![image](https://github.com/Himanshu2112000/Python_Or_Data_Analysis/assets/164239242/b17e4172-38fe-4a3a-af76-30a7e63a2fb8)

### The code snippet identifies categorical and numerical variables within a dataset using list comprehensions in Python. For categorical variables, it iterates through the columns and selects those with object data type ('O'). Similarly, for numerical variables, it identifies columns with non-object data types. This approach efficiently categorizes variables based on their data types, facilitating tailored data analysis and preprocessing. By separating variables into categorical and numerical groups, it enables targeted treatment and exploration, enhancing understanding and insights from the dataset.

## Filling missing values in Numerical data with the Median values.

![image](https://github.com/Himanshu2112000/Python_Or_Data_Analysis/assets/164239242/45426800-0e0f-4b68-bc24-40153011a0e6)

### The code iterates through each column in a DataFrame containing numerical data (num_data). For each column i, missing values are filled using the median value of that column. This process ensures that missing values in numerical columns are replaced with a central tendency measure, mitigating their impact on subsequent analyses. By applying this treatment across all numerical columns, the code enhances data completeness and integrity, enabling more robust statistical analysis and modeling.


# Filling missing values in Categorical data with the Mode values.

![image](https://github.com/Himanshu2112000/Python_Or_Data_Analysis/assets/164239242/b3c4fe21-305e-4d1f-8924-7ce2cd3885ba)

![image](https://github.com/Himanshu2112000/Python_Or_Data_Analysis/assets/164239242/6efc769e-7e86-4ccc-acc9-e7c614efc93c)

![image](https://github.com/Himanshu2112000/Python_Or_Data_Analysis/assets/164239242/854ceee2-536c-43e6-ac6d-465c0ba8a948)

![image](https://github.com/Himanshu2112000/Python_Or_Data_Analysis/assets/164239242/98b4f980-99a1-4cf7-b85a-e5adb538fba0)


### This code iterates through each column in a DataFrame containing categorical data (cat_data). For each column i, missing values are filled using the mode (most frequent value) of that column. This approach ensures that missing categorical values are replaced with the most common category, preserving the distribution of categorical variables. By applying this treatment across all categorical columns, the code enhances data completeness and prepares the dataset for further categorical analysis or modeling.


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

Detecting and treating outliers is crucial in data analysis to ensure the accuracy and reliability of statistical models. The Interquartile Range (IQR) method provides a robust approach for identifying outliers by calculating the range between the first and third quartiles. Data points lying outside the range of 1.5 times the IQR above the third quartile or below the first quartile are flagged as outliers. Subsequently, these outliers can be treated through various methods, such as replacing them with central tendency measures like the median or removing them entirely, depending on the dataset's characteristics and analysis objectives. This process enhances the quality of data analysis and improves the validity of insights derived from the dataset.


## Outlier treatment on all columns in num_data_2b

![image](https://github.com/Himanshu2112000/Python_Or_Data_Analysis/assets/164239242/30abfe6c-a374-4150-8471-02656501b6bb)

![image](https://github.com/Himanshu2112000/Python_Or_Data_Analysis/assets/164239242/49bd858d-687b-45e1-863e-be5e174ad911)

![image](https://github.com/Himanshu2112000/Python_Or_Data_Analysis/assets/164239242/bc793423-0e2e-42f3-9bce-81e7fc7ec554)

## Merging the categorical and the numerical data to get the dataset

![image](https://github.com/Himanshu2112000/Python_Or_Data_Analysis/assets/164239242/5e023eca-8d0a-4233-9713-6e971b314ec0)

Merging categorical and numerical data in Python involves combining datasets based on a common column or index using joins. Leveraging the merge() function from the pandas library enables seamless integration of disparate data types. This process facilitates comprehensive analysis by consolidating information from multiple sources into a unified dataset. By specifying join conditions and column identifiers, categorical and numerical data are merged into a cohesive structure, streamlining subsequent analytical workflows. Whether employing inner, outer, left, or right joins, this approach ensures the effective utilization of data across various domains, enhancing insights and decision-making capabilities.

## One-Hot Encoding: Conversion of categorical variables to continuous variables.

![image](https://github.com/Himanshu2112000/Python_Or_Data_Analysis/assets/164239242/9ae9d84c-0c09-44e7-b321-7ace81c0117a)

![image](https://github.com/Himanshu2112000/Python_Or_Data_Analysis/assets/164239242/ef1b8696-4dd9-49f6-8e23-b72e3ccfc931)

![image](https://github.com/Himanshu2112000/Python_Or_Data_Analysis/assets/164239242/455b55c0-4351-4992-843c-90be0bb5a189)

The code employs the get_dummies() function from the pandas library to conduct one-hot encoding on categorical variables within the DataFrame M_data1a. Specifically, it targets the 'Home_Ownership' and 'Loan_Purpose' columns, converting them into binary representations of their categories. This process generates new binary columns for each unique category present in the original columns, effectively transforming categorical variables into continuous ones. By encoding categorical data in this manner, the DataFrame becomes suitable for consumption by machine learning algorithms, facilitating predictive modeling and analysis tasks.


# Conculsion




















































