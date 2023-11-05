# Titanic Dataset Visualization with Seaborn
This code uses the Seaborn library to perform data visualization on the Titanic dataset. The dataset contains information about passengers on the Titanic, such as their survival status, class, age, gender, and more.

Before running the code, make sure you have the necessary Python libraries installed.
import seaborn as sns
import matplotlib.pyplot as plt

###Loading the Dataset
The Titanic dataset is loaded using Seaborn's built-in load_dataset function. 

###Data Cleaning
Missing values in the dataset are handled by filling them with zeros using the fillna method. 

##Data Visualization
###Heatmap of Missing Data
A heatmap is used to visualize missing data in the dataset. Columns with missing values are highlighted, making it easy to identify areas where data is missing.

###Fare and Age Distribution
Two histograms are created to display the distribution of fare prices and passenger ages. The number of bins and labels are customized for each plot.

###Countplots
Countplots are used to count and display the number of passengers who survived and the number of passengers in each passenger class.

###Joint Plot
A joint plot is created to show the distribution of fare prices in comparison to passenger age. The plot is customized to set limits on the x and y axes.

###Distribution of Fare Prices
A histogram is used to visualize the distribution of ticket fares. The x-axis is labeled as "fare," and limits are set for both the x and y axes.

###Boxplot
A boxplot is created to display the average age of passengers in each passenger class.

###Swarmplot
A swarmplot is used to show the age distribution in comparison to passenger class. A warning is issued for the points that cannot be placed.

###Gender Distribution
A countplot is used to count and display the number of male and female passengers.

###Titanic Heatmap
A heatmap is generated to show the correlation between different attributes of passengers on the Titanic, such as survival, class, age, and more. Correlation values are not displayed on the heatmap.

###Age Distribution by Gender
FacetGrid is used to create two histograms showing the age distribution for male and female passengers separately.
