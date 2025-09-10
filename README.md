Clinical Trial Data Analysis with Spark SQL

In this task, we are working with clinical trial data on behalf of a pharmaceutical company. The goal is to analyze trials registered in the USA to gain insights into the market.

The dataset for this assignment is provided as Clinicaltrial_16012025.csv, which contains over 500,000 records and can be treated as Big Data. 
Each row represents an individual clinical trial and includes details such as trial name, study type, study status, funding source, conditions, start date, and end date. 

We are required to use Spark SQL to answer the following questions:

1. Clinical Trial Types – List all trial types (from the Type column) along with their frequencies, sorted from most to least frequent.

2. Top 10 Conditions – Identify the 10 most common conditions with their frequencies.
   (Note that the Condition column may contain multiple conditions per record, which must be split and counted individually)

3. Average Trial Duration – For studies with an end date, calculate the mean trial length (in months).

4. Diabetes Trends – For studies with a non-null completion date and a status of Completed, c
   calculate how many related to Diabetes each year. Display the yearly trend using a suitable visualization.
