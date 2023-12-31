# Titanic Dataset Visualization with Seaborn
This code uses the Seaborn library to perform data visualization on the Titanic dataset. The dataset contains information about passengers on the Titanic, such as their survival status, class, age, gender, and more.

### Install Python libraries
Before running the code, make sure you have the necessary Python libraries installed.
import seaborn as sns
import matplotlib.pyplot as plt

### Loading the Dataset
The Titanic dataset is loaded using Seaborn's built-in load_dataset function. 

### Data Cleaning
Missing values in the dataset are handled by filling them with zeros using the fillna method. 

# Data Visualizations

## Heatmap of Missing Data
A heatmap is used to visualize missing data in the dataset. Columns with missing values are highlighted, making it easy to identify areas where data is missing.  <br>
![image](https://github.com/JonathanCPham/Titanic-Visualization/assets/49848126/59068645-8855-4fb1-a072-755f674426fe)

## Fare and Age Distribution
Two histograms are created to display the distribution of fare prices and passenger ages. The number of bins and labels are customized for each plot. <br>
![image](https://github.com/JonathanCPham/Titanic-Visualization/assets/49848126/6061f7d9-e2e8-4cef-bba6-57baf11c85ac)

## Bargraph
A bargraph was used to count and display the number of passengers who survived and the number of passengers in each passenger class. <br>
![image](https://github.com/JonathanCPham/Titanic-Visualization/assets/49848126/a209271d-e041-4c4b-af0c-3f29263a919f)

### A Bargraph showing different passenger classes. <br>
![image](https://github.com/JonathanCPham/Titanic-Visualization/assets/49848126/8b8a0148-2e0d-40c7-ac2d-9e93e00e90fa)

### A bar graph showing passenger genders. <br>
![image](https://github.com/JonathanCPham/Titanic-Visualization/assets/49848126/149ffe75-45c3-4bda-b385-57edb2fa0178)

## Joint Plot
A joint plot is created to show the distribution of fare prices in comparison to passenger age. The plot is customized to set limits on the x and y axes. <br> 
![image](https://github.com/JonathanCPham/Titanic-Visualization/assets/49848126/d2b8fffc-1550-4ecf-98b5-1881ca7d8404)

## Distribution of Fare Prices
A histogram is used to visualize the distribution of ticket fares. The x-axis is labeled as "fare," and limits are set for both the x and y axes. <br>
![image](https://github.com/JonathanCPham/Titanic-Visualization/assets/49848126/67e93614-7602-4806-8aef-cf98ce7f7a42)

## Boxplot
A boxplot is created to display the average age of passengers in each passenger class. <br>
![image](https://github.com/JonathanCPham/Titanic-Visualization/assets/49848126/3e4e3891-6b1c-402c-9fe8-133ab974f578) 

## Swarmplot
A swarmplot is used to show the age distribution in comparison to passenger class. A warning is issued for the points that cannot be placed. <br>
![image](https://github.com/JonathanCPham/Titanic-Visualization/assets/49848126/39990436-1c98-4115-b7a3-e774375f31c6)

## Gender Distribution
A countplot is used to count and display the number of male and female passengers. <br>
![image](https://github.com/JonathanCPham/Titanic-Visualization/assets/49848126/a21a4473-c8eb-4ea6-bae1-b652883f19d0)

## Titanic Heatmap
A heatmap is generated to show the correlation between different attributes of passengers on the Titanic, such as survival, class, age, and more. Correlation values are not displayed on the heatmap. <br>
![image](https://github.com/JonathanCPham/Titanic-Visualization/assets/49848126/47866212-2524-47f9-b793-c9cc2d7ddcb9)


### Age Distribution by Gender
FacetGrid is used to create two histograms showing the age distribution for male and female passengers separately. <br>
![image](https://github.com/JonathanCPham/Titanic-Visualization/assets/49848126/3b10b78f-55c1-4f1e-8a1b-132902c73fa1)

