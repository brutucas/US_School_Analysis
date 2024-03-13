# Unit 4 Homework Assignment: US School Analysis

![School Analysis](Images/school_analysis.png)

## Background
In this project, I explore the latest US Public Schools dataset, which was (unsurprisingly?) rich with information on public schools across the United States. I cleaned, examined, and created visual analysis of this data, with a particular focus on Student/Teacher ratios across states. 

**File:** [Schools Analysis Starter Code](Starter_Code/public_school_analysis.ipynb)

To begin, I created a new GitHub Repository for this project and cloned it locally to my machine. I also made sure to copy in any additional files and folders that I would need.

**Data Preparation:**

The project kicked off with the essential task of data preparation, involving reading and cleansing several CSV files for analysis. Using Pandas and the pd.read_csv() function, I loaded and read in datasets (assinging to some appropriate variables), including school characteristics, locations, and a data dictionary.

I worked to achieve the following:
- ensure consistency in unique identifiers across the datasets;
- merge location and characteristic data to form a unified analysis base;
- filter the dataset to focus on regular schools.

**Data Cleaning:**

Once I had prepared the data, I moved onto the task of data cleaning and visualisation. This phase was crucial for handling null values and identifying outliers that could easily skew my data analysis. 

I used the following strategies:
- checked for null values in the dataframe with information on regular schools;
- filled some of the columns with 0 where appropriate and rechecked null values;
- dropped any remaining null values and re-verified that all null values were absent.

**Analytical Deep Dive:**

Following this, I explored the data visually through histograms, which provided insight into the data distribution across different metrics, and used this information to further filter the datasets. 

Then it was time for the core of the project - an analytical exploration of the Student/Teacher Ratios across states. Key steps in this phase included:
- generating correlation heatmaps to uncover relationships between different school characteristics;
- conducting a geographic analysis to visualize school locations and focus on state-specific data;
- calculating average Student/Teacher Ratios by state and comparing these to national averages.

**Insights and Observations:**

In this phase, I wanted to avoid simply crunching numbers, but instead understand the story behind the data. How do student-to-teacher ratios vary across states? What factors might contribute to these differences?

The analysis revealed significant differences in student-to-teacher ratios across the United States. Some interesting correlations emerged, such as the relationship between school size and student-to-teacher ratio, and geographical concentration of som 'non-white' demographics to certain regions (e.g. more Hispanics in the southern regions of the US). offering avenues for further exploration.

The specific analysis of my adopted 'home state' added a personal dimension, allowing me to compare Virginia's performance against national benchmarks. There is definitely potential to further explore and analyse this schools data to identify improvements the allocation of educational resources in Virginia and further afield.

**Reflections and Conclusions:**

Reflecting on the project, I recognize the importance of early-stage data cleaning decisions and their impact on analysis outcomes. The exploration of this dataset has opened my eyes to the myriad of ways data can inform and improve educational policies and practices.

This project was a deep dive into the heart of US public school education, and underscored the critical role of data analysis in shaping educational landscapes. By leveraging data, we can uncover insights that lead to meaningful improvements in how education is delivered. 

As cliched as it might sound, the effective cleaning, analysis, and application of data could (in this particular case) significantly contribute to ensuring that every student has access to quality learning environments.


