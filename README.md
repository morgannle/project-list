# A list of projects that I have done:

# 1. Pandemic simulation
An app to simulate behavior of a pandemic. This app used SEIR model to simulate behavior of a viral outbreak, you can modify various parameters to see their effects. Please note that this app is for educational purpose only and can not be used to model a real outbreak. You can access the app [here.](http://ec2-18-188-192-168.us-east-2.compute.amazonaws.com:3838/simulation/)

Github: https://github.com/nghiale5991/pandemic_simulation

Tech used: Rshiny, R, Amazon AWS.

# 2. COVID 19 dashboard
This dashboard is to inform people of the pandemic situation in US as well as their state. Data is provided by CDC and The New York Times. You can access the dashboard with this [link](http://ec2-18-188-192-168.us-east-2.compute.amazonaws.com:3838/myapp).

Github: https://github.com/nghiale5991/covid_dashboard

Tech used: Rshiny, R, Amazon AWS, Leaflet map.

# 3. COVID 19 pre-existing conditions analysis

SARS-CoV-2, a novel corona virus which causes COVID-19, the respiratory illness responsible for the COVID-19 pandemic. The World Health Organization declared the outbreak a Public Health Emergency of International Concern on 30 January 2020, and a pandemic on 11 March 2020. Until today (August 1st, 2020), the virus has infected over 18 millions, and claimed the life of nearly 700,000 people. The pandemic not only caused the biggest health crisis of the 21st century so far, but it also triggered a global economic recession. Til this day we still know very little about this virus but how it transmits, we already know that old people and people with pre-existing condition(s) are the most vulnerable demographic, but there are little studies conducted to quantify risks associate with a specific age or condition. This project tries to quantify and estimate risks associate with a certain conditions and age groups. You can access the report [here](https://nghiale5991.github.io/covid19-precondition-analysis/report.html).

Github: https://github.com/nghiale5991/covid19-precondition-analysis

Tech used: R

# A list of custom functions that I have developed:

# 1. Feature selection using LASSO
 
The output of the function is a formula object that can be feed to glm or lm function. The first input is the dataframe, the second input is the name of the response variable, should be inside double quote, something like "response_variable".

Github: https://github.com/nghiale5991/lasso

Language: R
