## Exploratory Data Analysis (EDA) on Dune Sales Dataset

#### Introduction
This project performs an Exploratory Data Analysis (EDA) on the Dune Sales dataset. The primary objective is to understand the dataset, clean it, perform feature engineering, visualize key insights, and draw meaningful conclusions. Below is a summary of the steps taken and challenges encountered during the analysis.

**Loading the Data**
   - Imported essential libraries such as pandas, numpy, matplotlib, seaborn, and missingno.
   - Loaded the dataset from a CSV file into a pandas DataFrame.

**Data Understanding**
   - Displayed the first few rows of the dataset to understand its structure.
   - Checked the dataset's info, columns, and shape to get an overview of the data types and dimensions.

**Data Cleaning**
   - Checked for missing values in the dataset.
   - Visualized the missing data using the missingno library.
   - Dropped rows with missing data to ensure a clean dataset.
   - Verified that all missing values were handled.

**Feature Engineering**
   - Converted the 'Date' column into a pandas datetime object.
   - Extracted year, month, quarter, and other relevant time-based features.
   - Created pivot tables to summarize data by different features like 'Year', 'Month', 'Customer Gender', and 'Age Group'.

**Data Visualization**
   - Used seaborn and matplotlib to create various plots such as line plots, bar plots, and heatmaps.
   - Visualized relationships between 'Profit' and other features like 'Month', 'Year', 'Customer Gender', and 'Age Group'.
   - Analyzed correlations between numerical features using a heatmap.

**Insights and Conclusions**
   - Summarized key insights and conclusions drawn from the EDA.
   - Discussed the patterns observed in profit trends, customer demographics, and other relevant aspects of the dataset.

#### Challenge Encountered
- **Missing Data**: The dataset initially contained missing values, which were handled by dropping the affected rows. This approach was chosen to maintain data integrity for analysis.
- **Data Transformation**: Converting date columns and extracting time-based features required careful handling to ensure accurate analysis.
- **Visual Representation**: Creating clear and informative visualizations was essential to derive meaningful insights, which required fine-tuning of plot parameters.

#### Conclusion
The EDA on the Dune Sales dataset provided valuable insights into sales trends, customer demographics, and profit patterns. The analysis highlights the importance of thorough data cleaning, feature engineering, and visualization in understanding and leveraging data effectively.

**Contributing & Commenting:**

Contributions to this analysis are welcome. You can reach out to me using my contact below for gigs and collaborations.

**Contact:**

ike@ikemefulaoriaku.space | (https://www.linkedin.com/in/gentleiyke/)
