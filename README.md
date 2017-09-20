# StudendLoans

This project is about solving the following challenge:

##Challenge: Predict Students’ Ability to Repay Educational Loans
Claire SmithInstructorProjects and Portfolio Ideas

This challenge was provided by Michael Boerrigter

The deadline for this challenge is October 27th 2017

Submit an entry for this challenge

If you have any questions about this challenge please post them below

General challenge FAQ

Using Institutional Features to Predict Students’ Ability to Repay Educational Loans

Overview:

Testing to see if a set of institutional features can be used to predict student outcomes, in particular debt repayment.

Basic Information:

Length – estimated total about 20-25 hours for someone familiar with data analysis.
Group Size – Solo or group of two to four.
Difficulty – Intermediate, mostly because of the extensive data exploration and wrangling involved.
Prerequisite Knowledge – You need to be familiar with feature selection and dimensionality reduction as well as different machine learning algorithms that can predict a numerical value (basically some sort of regression).
Required Technology – R or Python because the deliverable is either an Rmarkdown or Python notebook.
Background

Background/Context – The choice of a particular college can dramatically influence a person’s future not in the least that of job opportunities. Since most students will incur a significant amount of debt over the course of their study program, it is vitally important that job opportunities after obtaining a certificate, undergraduate, or graduate degree will allow one to repay the debt without having to forego the necessities of living. This project explores to what extent institutional characteristics as well as certain demographic factors can indicate/predict debt repayment.
Target Audience – Universities and colleges, advisors, students and students’ families.
Portfolio Development – This project showcases your ability to analyze a complex dataset and determine whether it is useful for addressing a question.
Details

Description - In today’s economy, higher education is no longer a luxury, but a necessity for individual economic opportunity, as well as a country’s competitiveness in the global economy. Many institutions offer high-quality, affordable educational experiences that expose students to new fields of thought and prepare them to be engaged and productive citizens in their communities. However, some schools do not serve their students well; for instance, they may charge prices that make higher education increasingly out of reach or fail to support students through to completing their education and obtaining well-paying jobs. The (US) “College Scorecard” is designed to provide students, families, and their advisers with a truer picture on college cost and value, and includes the most reliable national data on the earnings of former college graduates and new data on student debt.

Success Criteria – A successful submission does not necessarily need to find the best accuracy but does take the following into account:

Employs either R or Python. The deliverable is either an iPython notebook, an Rmarkdown file or a PDF from either of the aforementioned formats.
Contains the actual, annotated, code used to explore the data and develop a model.
Uses cross-validation.
Accuracy is assessed using the root mean squared error (RMSE). As a guideline, the RMSE should be a maximum of 10-11 on the hold-out from the training data but lower values are definitely attainable.
Although not strictly necessary, it would be useful to handle ‘groups’ of features that share a characteristic(s) and have a certain amount of ‘missingness’.
Explains which year(s) were used for training and test sets respectively. Not that it is perfectly acceptable to use one year (e.g., the last) and split it into training, validation, and test sets. Your choice should be justified though.
Potential Pitfalls

Features may display ‘missingness’ and different types of features may need a different imputation approach.
The response variable is also present in disaggregated forms, a decision needs to be made which of these disaggregated forms, if any, will be used.
The number of features is fairly large and, as such, it may be counterproductive to try to investigate each feature (or group of features) by itself.
Data Access and Usage limitations - All data is public data.

The data is available at:

https://ed-public-download.app.cloud.gov/downloads/Most-Recent-Cohorts-All-Data-Elements.csv. Note that the data file contains the data for the most recent cohort. If you are interested in all preceding cohorts you can find the data at https://ed-public-download.app.cloud.gov/downloads/CollegeScorecard_Raw_Data.zip.

Documentation for the data is available at https://collegescorecard.ed.gov/data/documentation/. Here, you can also download the data dictionary (https://collegescorecard.ed.gov/assets/CollegeScorecardDataDictionary.xlsx).