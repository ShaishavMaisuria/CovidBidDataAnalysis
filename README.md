# CovidBigDataAnalysis

**Topic:** Covid-19 Data Lake analysis

**Team Members:** Anuj Sharma, Aayush Patel, Shaishav Maisuria, Ishani Naik, Kautilya Kondragunta

**Communication Plan:**
Members of the team will most likely communicate using online platforms such as Zoom and Google Meet. Each team member will most likely be allocated tasks that contribute to the project based on their strengths and weaknesses. Any team members experiencing trouble will most likely arrange up "doubt scrum meetings" with other team members who have domain knowledge on that topic. In addition, each Team member will most likely participate in a weekly scrum during which all project components will be tested, explained, and improved before submission. Based on the task requirements for that week, team members will likely gather on Friday for a "doubtScrum meeting" and Sunday for a "Weekly scrum meeting" from 6:00 pm to 10:00 pm. The goal for each week is to submit the assignment one day before the deadline, which is Monday. 

**Introduction to Problem:**
AWS Covid-19 data lake is open source. In our project, we will be using this dataset for analysis using AWS. Building models could do the research for forecasting Covid-19 hotspots, arranging beds and ventilators based on the new cases and trends, and checking vaccine availability in various cities. We want to predict several other movements related to the pandemic.

**Research Questions:**

* How many people were tested, pending tests, and positive and negative tests for COVID-19?

* What percentage of the population took the vaccine?

* What is the trend of the virus (are the daily cases rising or are they decreasing)?

* What percentage of the population is hospitalized?

# [Dashboard](https://github.com/ShaishavMaisuria/CovidBigDataAnalysis/blob/main/Dashboard.pdf)

## [Quicksight Dashboard](https://us-east-1.quicksight.aws.amazon.com/sn/dashboards/8f93d70b-6512-44b7-a44e-c6c934a24c06/views/1de9c094-0f48-4242-98e4-9151c9244abe)

## Viz 1
- As can be seen from the graph, the total number of deaths during the early period is negligible, but as time passed, the mortality rate rose to 205,859 on September 29, 2020.

## Viz 2
- We were able to identify the covid analysis based on the total of Patients in ICU and Patients' ventilators.
- The total number of patients in the ICU surpasses the total number of patients on ventilators.

## Viz 3
- The graph depicts the number of persons that tested positive/negative following a test.
- As can be seen, some fewer people test positive, with New York State topping the list.

## Viz 4
- The graph shows the number of patients admitted to hospitals per state.
- Compared to other states, California, New York, and Texas have the most significant number of hospitalized patients.

## Viz 5
- The graph depicts the overall number of patients who could recover after testing positive.
- When comparing Viz4 and Viz5, Texas has a more significant percentage of patients who recover than those who are hospitalized.

## Viz 6
- The graph depicts the total number of positive tests by state.
- California, New York, Texas, and Florida are among the highest-rated states compared to others.

## Viz 7
- The graph depicts the number of patients in the intensive care unit (ICU) and those on ventilators.
- The number of ICU patients in California is higher than in New Jersey. On the other hand, patients on ventilators are in the opposite situation.

**Analytics and Evaluation**

For applying machine learning algorithms to predict deaths due to covid -19, the data was split into 70-30 ratio for training and testing respectively. To predict deaths according to the states, we used 3 machine learning models to evaluate and find out which model gives the best result. The metrics we used to evaluate the models were: R squared score,Mean squared error and Mean absolute error.The models we used were: 

- Linear Regression
- Random Forest Regression
- Logistic Regression


**Data Resource:**

* Dataset: https://dj2taa9i652rf.cloudfront.net/

* Registry: https://registry.opendata.aws/aws-covid19-lake/

**Narrated Presentation**
Google Drive Link: https://drive.google.com/file/d/1YfEm105sXQzn481UpjPPgm5FC1vWOT9b/view?usp=sharing
