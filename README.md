# Aziksa Summer Internship 2023
## Problem Statement: 
Aziksa is a blended e-learning company that teaches a multitude of languages to employees in foreign corporate national companies. Aziksa boasts a 60% pass rate of students compared to the leading competition who are only able to retain under 10% of users to pass (Duolingo, Babbel, Learnlight). The reason for Aziksa’s incredibly high pass rate is due to their blended e-learning style that fuses e-learning content with human interaction. For every language learning course, Aziksa has a dedicated staff called dynamizers that manually monitor the progress of students and contact them with resources and support throughout the duration of the course. However, as Aziksa has grown, class sizes and student population have increased over capacity for dynamizers to manually monitor progress. Aziksa wanted to create a machine learning model that is able to use in app statistics in order to predict which students are least likely to pass the course in order to focus dynamizer attention on them first. This would alleviate the growing stress of dynamizers having to manually comb through thousands of students' data and personally deciding which to contact first. 

## The process:
1. Understand the problem
2. Get the data
3. Data analysis
4. Data cleaning
5. Model iteration 
###### please note that all links are set to view only and all data files have been restricted so that you may not view sensitive information

## Understand the problem
* Held weekly meetings with dynamizers to understand course logistics and their side of the problem 
* Understand patterns they have seen in order to prove or disprove after combing the data 
* Present an example machine learning project to the team to illustrate my possible solution to their problem. Received feedback
* [Link to Machine Learning Demo Presentation](https://docs.google.com/presentation/d/18-qsUJYI6FT9tX60zWAsUWtvUgs1DPFywsYDo3KnAmQ/edit#slide=id.g2591ba788d6_0_91)
* [Link to Machine Learning Demo Code](https://colab.research.google.com/drive/1folQzfDUe80ji5hGzar2X3sf4heby6GD)
* [Link to Machine Learning Data Illustration code](https://colab.research.google.com/drive/18hxYq-BQm9JKK31ja_842tifrOjVbQE2?usp=sharing)

## Get the Data
* Data stored in AWS Relational Data Storage (RDS) located in Virginia 
* Database contained hundreds of tables. Extracted user behavior related data
* Wrote SQL script to grab data into CSV files. Imported CSV files into Google Colab to begin data analysis 

## Data Analysis
* Received three possible theories from dynamizers. Used the data to investigate validity of theories
* Used correlation matrices, matplot lib graphs, seaborn library heatmaps to illustrate and find relationships 
* [Link to Data Findings Presentation](https://docs.google.com/presentation/d/1i52wnL_rLT9_d4LqCXGBjfcd_nAnvQWVLewaKSJmTxg/edit#slide=id.p)
* [Link to Code behind Data Findings Presentation](https://colab.research.google.com/drive/1U6TaU28_yaU-Ow8WxLlrTqGnIDVyqXS0)

## Data cleaning 
* Data contained hundreds of features. Needed to find which features were indicators of student success 
* Using pandas dataframes, merged all data into one data table. Included pivoting tables, querying files, and filtering out certain data 
* Created new features not originally collected such as: number of days it took the user to take the placement test, time spent per week, number of days since the last login
* [Link to 2nd Data Findings Presentation](https://docs.google.com/presentation/d/1W8LsgXG1Q7He433mF5nHhWijcybu3A2ohfbsxiaS5Wk/edit#slide=id.p)
* [Link to code behind 2nd Data Findings Presentation](https://colab.research.google.com/drive/1OURLVd2Veusb3A7FM5d07fKYRUjUQCdZ)

## Model Iteration
* Created over eight different models with varying features and prediction values 
* Used linear regression, decision trees, and random forrest regression
* Final model predicts failing student with 85% accuracy on test data (used K- fold cross validation)
* [Link to Model Analysis Presentation](https://drive.google.com/file/d/1ytVJz9xzXWkaXksm3pSVuQ3Cwa9pZ2qN/view?usp=sharing)
* [Link to Model Analysis Code](https://colab.research.google.com/drive/1s6MSd_SzlVYRH9U92r44dAsKSPlispJG)
