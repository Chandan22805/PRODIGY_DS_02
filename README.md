# Titanic Dataset Analysis

This repository contains an exploratory data analysis (EDA) project conducted on the Titanic dataset as part of an internship assignment. The project includes various analyses and visualizations aimed at understanding the data and uncovering insights related to passenger demographics, survival rates, and more.

## Repository Structure

- `Task_2.ipynb`: The Jupyter Notebook containing the complete EDA process, including data loading, cleaning, visualization, and insights.

## Project Overview

### Objective
The goal of this project is to perform a thorough exploratory data analysis on the Titanic dataset to understand key factors influencing passenger survival and to provide actionable insights based on the data.

### Dataset
The Titanic dataset is a classic dataset used in machine learning and data analysis. It includes information on passengers who were aboard the Titanic, including their age, class, gender, fare, and survival status.

### Key Analyses
- **Data Cleaning**: Handling missing values, correcting data types, and ensuring data quality.
- **Descriptive Statistics**: Calculating summary statistics to understand the distribution of key variables.
- **Visualization**: Creating various plots to visualize the relationships between different variables, such as:
  - Age distribution across different classes.
  - Survival rates by class and gender.
  - Fare distribution and its relationship with passenger class.
- **Feature Engineering**: Creating new features such as `individual_fare`, calculated as the total fare divided by the number of people sharing the same ticket.

## Key Visualizations

### Box Plot
- **Age vs. Pclass**: A box plot to understand the age distribution across different passenger classes.

### Bar Plot
- **Survival vs. Gender**: A bar plot showing the survival count for each gender, broken down by class.

### Pie Chart
- **Pclass Distribution**: A pie chart visualizing the proportion of passengers in each class.

## Installation and Usage

### Prerequisites
- Python 3.13.1
- Jupyter Notebook
- Pandas, Matplotlib, Seaborn, scikit-learn libraries
