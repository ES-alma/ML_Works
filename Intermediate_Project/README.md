#Customer Segmentation using Clustering

##Description

The objective of this project is to perform customer segmentation using clustering techniques.
The goal is to group customers based on their demographic characteristics and purchasing behavior, enabling better understanding of customer patterns and supporting targeted marketing strategies.

##Dataset

Source: Kaggle (Customer Personality Analysis Dataset)
https://www.kaggle.com/datasets/vishakhdapat/customer-segmentation-clustering/data

Description:
The dataset contains information about customers, including demographic details (age, marital status, income), household composition (number of children and teenagers), and purchasing behavior across various product categories such as wine, meat, fruits, and other goods.

##Steps Performed

1.Data Cleaning:
Handled missing values in the Income column using mean imputation
Checked and confirmed absence of duplicate records

3.Exploratory Data Analysis (EDA):
Examined dataset structure using summary statistics and data types
Analyzed distributions of income, spending, and demographic variables

4.Feature Engineering:
Created Age from Year_Birth
Derived Enrollment_Duration from Dt_Customer
Grouped and encoded categorical variables using one-hot encoding

5.Data Preprocessing
Removed irrelevant features such as ID and constant variables
Applied StandardScaler to normalize features

6.Visualization
Used Elbow Method to determine optimal number of clusters
Used Silhouette Score to validate cluster quality
Visualized clusters using scatter plots

7.Model Building
Applied K-Means clustering algorithm
Selected optimal number of clusters (k = 4) based on evaluation metrics

##Results

The model identified four distinct customer segments:
   High-income premium customers with high quality products spending behavior
   Low-income budget customers with minimal spending
   High-value customers with the highest purchasing activity
   Family-oriented customers with moderate and balanced spending
   
Key Findings:
Income strongly influences purchasing behavior
Customers with fewer dependents tend to spend more on premium products
Clear segmentation exists, enabling targeted business strategies

##Tools Used:

Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn

##Conclusion

The clustering approach successfully segmented customers into meaningful groups based on their behavior and characteristics. These insights can help businesses design targeted marketing strategies, improve customer engagement, and optimize product offerings. The project demonstrates the effectiveness of K-Means clustering in solving real-world business problems.

##Author

Alma
