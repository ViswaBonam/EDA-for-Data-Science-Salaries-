# EDA for Data Science Salaries
Exploratory Data Analysis of the salaries of data science jobs.
* Operations performed on the dataset:
1. Data Cleaning
2. Data Analysis
3. Questions answered using the dataset: 
   * Average salary based on the experience level of the employees
   * How many data science jobs are present for a given country?
   * Average salary for the top 10 countries
   * Which data science roles pay the hightest?
   * Variation of data science job salaries over the years
   * Company Analysis
   * Distribution of remote employees
   * Job title and number of employees
   * Data Sceince Salaries by Company Size  

# Data fields

Here's a brief version of what you'll find in the data description file.

* work_year:	The year the salary was paid.
* experience_level:	The experience level in the job during the year with the following possible values: EN Entry-level / Junior MI Mid-level / Intermediate SE Senior-level / Expert EX Executive-level / Director
* employment_type:	The type of employement for the role: PT Part-time FT Full-time CT Contract FL Freelance
* job_title:	The role worked in during the year.
* salary:	The total gross salary amount paid.
* salary_currency:	The currency of the salary paid as an ISO 4217 currency code.
* salary_in_usd:	The salary in USD (FX rate divided by avg. USD rate for the respective year via fxdata.foorilla.com).
* employee_residence:	Employee's primary country of residence in during the work year as an ISO 3166 country code.
* remote_ratio:	The overall amount of work done remotely, possible values are as follows: 0 No remote work (less than 20%) 50 Partially remote 100 Fully remote (more than 80%)
* company_location:	The country of the employer's main office or contracting branch as an ISO 3166 country code.
* company_size:	The average number of people that worked for the company during the year: S less than 50 employees (small) M 50 to 250 employees (medium) L more than 250 employees (large)

# Observations made from the analysis
1. Average salary based on the experience level of the employees
![](Visualizations/experience_level%20vs%20salary_in_usd.png)
From the above plot, the mean salary for each experience level is given as
* Mid Level : 76.94K USD
* Senior Level : 135K USD
* Entry Level : 56.5K USD
* Executive level : 171.437K USD

2. How many data science jobs are present for a given country? 
![](Visualizations/jobs%20per%20country.png)
From our observation
* United states has 318 jobs
* United Kingdom has 46 jobs
* Canada, Germany and India have 28,27 and 24 jobs respectively
(These are the number of jobs as per the given dataset)

3. Average salary for the top 10 countries
![](Visualizations/Top%2010%20countries-%20avg%20salary.png)
* Russia pays the highest average salary among all the countries in the dataset at 157.5K USD
* United States takes the second position with 144.3K USD
* New Zealand and Israel pay 125K USD and 119K USD respectively

4. Which data science roles pay the hightest?
![](Visualizations/avg%20salary%20per%20job%20title.png)
* Data Analytics lead and Principle Data Engineer pay the highest around 405K USD and 328.34K USD respectively

5. Variation of data science job salaries over the years
![](Visualizations/experience_level%20vs%20salary_in_usd%20over%20years.png)

6. Company Analysis
![](Visualizations/company%20size-%20pie%20chart.png)

7. Distribution of remote employees
![](Visualizations/distribution%20of%20remote%20employees.png)

![](Visualizations/distribution%20of%20jobs%20over%20years.png)
* There is a significant improvement in the number of remote jobs from 2020 to 2022.

8. Job title and number of employees 
![](Visualizations/top%2010%20data%20science%20roles.png)
* Data Scientist role has the 130 of jobs in the dataset
* Following which roles of Data Engineer and Data Analyst are the next popular roles

9. Data Sceince Salaries by Company Size
![](Visualizations/salaries%20based%20on%20company%20size.png)

# Dataset
The dataset has been taken from [kaggle](https://www.kaggle.com/datasets/ruchi798/data-science-job-salaries)

