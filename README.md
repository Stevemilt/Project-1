# Heart Shaped Box : An Exploration and Harnessing of Data on Cardiovascular Disease (CVD)

## Team Members
Stephen Milton
Anthony Elbers
Divya Gururajan Sumangala
Brett Wallis
Nalishebo Meebelo

## Summary
A deep dive in to the Cardio Vascular data set to identify existing trends and relationships between Gender, Age, Cholesterol, BP, BMI etc..

## Questions to be answered through the analysis.
* Which gender (male or female) is more likely to have CVD?
* Does age influence the potential risk factor of CVD?
* What type of lifestyle variables can increase the potential of contracting CVD?

## Data Cleanup & Exploration Process
### Exploration and cleanup process 
* 3 CSV files downloaded
* Converted CSV using Pandas Dataframe 
* No null values found in the Dataset
* Calculated and created BMI and Blood Pressure Columns 

## Challenges:
* Tried to unite 2 raw Datasets with different headers and observations
* Smaller data set had numerous null values. Once removed there was not enough data to make a significant impact on the larger dataset. 
* Inability to interpret available data from APIs

## Insights:
* Discovered majority of data contained dichotomous variables 
* Developed Logistic Regression to establish correlation between variables 
* Developed Contingency Tables 
* Developed a Predictive Model

## Solutions: 
* Resolved to use one Dataset due to mismatch in headers and duplicate data
* Opted not to include APIs in the project

## Tools & Libraries
  * Python
    * Pandas
    * Matplotlib 
    * Scipy 
    * Statsmodel
    * Sklearn 
    * Numpy
    * Seaborn
    
 ## Tables and Graphs
   * Bar
   * Pie
   * Hist
## Machine learning
  Logistic Regression

## Data Analysis Screenshots
![image](https://user-images.githubusercontent.com/68937366/112089286-4e689c80-8bcc-11eb-9a5e-003f0b119d29.png)

![image](https://user-images.githubusercontent.com/68937366/112089350-6d672e80-8bcc-11eb-9f67-7c097cae6266.png)

![image](https://user-images.githubusercontent.com/68937366/112089367-76f09680-8bcc-11eb-9385-69fed813b140.png)

### Logistic Regression to find correlations with Chi2 (Chi Square)

![image](https://user-images.githubusercontent.com/68937366/112089394-866fdf80-8bcc-11eb-8c9b-0542e1f5e46d.png)

![image](https://user-images.githubusercontent.com/68937366/112089417-98518280-8bcc-11eb-9d47-303999cd472a.png)

![image](https://user-images.githubusercontent.com/68937366/112089443-a43d4480-8bcc-11eb-8368-2c7e4317dc43.png)

## Conclusion
 * Gender was not a contributing factor to CVD
 * As Age progresses the chance of CVD increases (especially after age 55)
 * High Cholesterol levels indicate an increased chance of CVD.
 * Blood Pressure levels above 120 had a direct correlation with CVD.
 * Patients with a BMI index of Overweight and Obese have a higher chance of CVD.
 * Patients who exercise are less likely to contract CVD in comparison to those who do not exercise.
 * Predictive analysis, using logistic regression model we were able to have an accuracy level of 72%

## Limitations
 * Missing variables contributing to CVD: Nutrition, dietary, location, socio-economic factors.
 * Unable to present more variety of visualizations due to categorical data.    




