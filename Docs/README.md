# Titanic Dataset Analysis
This project analyzes the Titanic dataset from Kaggle to determine if survival rate is associated with the class of passenger, gender, and age. The project includes exploratory data analysis using Python and statistical analysis to draw conclusions about the relationships between these variables.

## Project Structure <br/>
This project is organized into several folders:

Src: Contains the Jupyter notebook file that includes the code used for the analysis.<br/>
Data: Contains the csv files used for the analysis.<br/>
Docs: Contains the readme file summarizing the findings from the analysis.<br/>
Results: Contains the statistics and the plots generated along with the explantions.<br/>

## Hypotheses <br/>
The following hypotheses were tested in this analysis:<br/>

Hypothesis 1: The survival rate is associated with the class of passenger.<br/>
Hypothesis 2: The survival rate is associated with gender.<br/>
Hypothesis 3: The survival rate is associated with age.<br/>

## Analysis and Results
The analysis involved exploratory data analysis, and statistical analysis using Python libraries. <br/>
For hypothesis 1, a bar graph was generated to show the relationship between the survival rate and passenger class. The graph showed that passengers in first class had a higher survival rate compared to those in second and third class.<br/>
For hypothesis 2, a bar graph was generated to show the relationship between the survival rate and gender. The graph showed that females had a higher survival rate compared to males.<br/>
For hypothesis 3, a bar graph was generated to show the relationship between the survival rate and age group. The graph showed that children had the highest survival rate, followed by adults, and then the elderly.<br/>

## Conclusion
The analysis revealed that survival rate on the Titanic was associated with passenger class, gender, and age. Passengers in first class, females, and children had higher survival rates compared to their counterparts. This analysis provides valuable insights into the factors that affected survival rates on the Titanic. <br/>
<br/>
<br/>
<br/>
<br/>

# House Price Dataset Analysis
This project aims to perform Exploratory Data Analysis (EDA) on the House Price Dataset. The dataset is obtained from Kaggle, and the train.csv file is used for analysis.

## Project Structure <br/>
This project is organized into several folders:

Src: Contains the Jupyter notebook file that includes the code used for the analysis.<br/>
Data: Contains the csv files used for the analysis.<br/>
Docs: Contains the readme file summarizing the findings from the analysis.<br/>
Results: Contains the statistics and the plots generated along with the explantions.<br/>

## Libraries Used <br/>
The following libraries are used in this project: <br/>
pandas<br/>
numpy<br/>
matplotlib<br/>
seaborn<br/>

## Summary of Findings
EDA is performed on the House Price Dataset to gain insights and understand the relationships between the different variables. The following are the key findings:<br/>
The dataset has 1460 observations and 81 variables.<br/>
The LotFrontage column has 259 missing values, and this is likely due to the fact that not all houses have a street connected to the property.<br/>
The target variable SalePrice is right-skewed and has some outliers.<br/>
The variable OverallQual has a distribution that is skewed to the right, indicating that most houses in the dataset are of good quality.<br/>
The variable LotArea has a distribution that is heavily skewed to the right, indicating that most houses have small lot areas.<br/>
There is a strong positive correlation between GrLivArea and SalePrice, indicating that larger houses tend to have higher sale prices.<br/>
There is a moderate positive correlation between OverallQual and SalePrice, indicating that houses of higher quality tend to have higher sale prices.<br/>
