#Tech Layoffs Analysis Using Python
##Project Overview

This project analyzes global technology sector layoffs to uncover trends, patterns, and potential reasons behind workforce reductions.
The analysis focuses on factors such as company size, location, industry type, layoff percentage, and funding stage.

Notebook: Techlayoff.ipynb
Dataset: tech_layoffs.csv

Performed data cleaning and preprocessing

Handled missing values and removed duplicates

Conducted exploratory data analysis (EDA) using visualizations

Analyzed trends over time and by region, company, and industry

Interpreted key insights about global tech layoffs

#Technologies & Libraries Used

| Library              | Purpose                                      |
| -------------------- | -------------------------------------------- |
| Pandas               | Data loading, cleaning & manipulation        |
| NumPy                | Numerical operations                         |
| Matplotlib & Seaborn | Data visualization                           |
| Plotly               | Interactive visualizations                   |
| Scikit-Learn         | (If applied) model building or preprocessing |
| Jupyter Notebook     | Analysis and visualization environment       |

#Dataset Description
| Column                | Description                                               |
| --------------------- | --------------------------------------------------------- |
| company               | Name of the company that conducted layoffs                |
| location              | Location of the company                                   |
| industry              | Industry or sector of the company                         |
| total_laid_off        | Total number of employees laid off                        |
| percentage_laid_off   | Percentage of employees laid off                          |
| date                  | Date when layoffs occurred                                |
| stage                 | Company’s funding stage (e.g., Startup, Series A, Public) |
| country               | Country where layoffs took place                          |
| funds_raised_millions | Total funds raised by the company (in millions)           |

#Steps Performed
##1. Data Preprocessing

Loaded the dataset using Pandas

Checked for missing and duplicate records

Converted date column to datetime format

Filled missing values appropriately

Removed outliers and standardized categorical values

##2. Exploratory Data Analysis (EDA)

Analyzed total layoffs by year and month

Compared layoffs across industries and countries

Identified top 10 companies with the highest layoffs

Explored percentage_laid_off vs funds_raised_millions

Used bar plots, line plots, and heatmaps for visualization

##3. Visualization

Layoffs over time: Identified major spikes in specific years

Industry-wise comparison: Highlighted sectors most affected

Geographical insights: Countries/regions with the largest layoffs

Company funding vs layoffs: Explored financial correlation

#Conclusion

This project provides insights into how global economic conditions, funding, and industry trends have impacted the tech job market.
It reveals that layoffs tend to increase during periods of financial uncertainty and that startup-stage companies are more vulnerable to funding shortages.
