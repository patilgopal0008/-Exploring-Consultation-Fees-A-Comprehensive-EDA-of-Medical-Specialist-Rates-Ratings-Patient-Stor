# consultation-fee-analysis-using-python

Exploratory Data Analysis
The main objective of the project is to analyse   doctor’s based on their city, specialization, stories and experience


For web scraping website used is Practo.
Practo Search is a patient focused, unbiased, independent medical website  Patients can book confirmed appointments with doctors listed on Practo's website from this websites the information like doctor’s name, area, city, consultation fee, rating, experience and stories of the patients who has got treated by the doctors by using python modules :
Numpy
Pandas
matplotlib
Seaborn
Regex , beautifulsoup & requests
# about data
The data frame consists of the 9 columns which includes both numerical and categorical data
The data consists of the categorical columns  like area, city and stories
 it also has  numerical data columns like consultation fee, rating, experience and the stories

# Data cleaning & Manipulation–
After forming the data frame the null values are
present  in the numerical columns  consultation fee, rating,
experience and stories .
the null values consulation fee column has replaced by using group by of specialization  because the consultation fee will be different for different specialization The null values in rating has filled with median of that column because the rating is Depends on his treatment it does not have relation with other columns   also the Experience null values replaced with median of that column and the stories null values replaced by using group by of the experience column because the stories increases No of years of experience

