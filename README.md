# Introduction

This document details the processes involved in developing data visualizations for three separate capstone projects.

# Project 1: Employee Satisfaction Analysis

## Project Overview

This section details the process of developing visualizations for a data analysis project focused on employee satisfaction, leveraging a pre-defined set of ten survey questions.

## Data Exploration

Data Review: The project began with a 5-minute review of the data dictionary and survey data in Excel.
Data Cleaning: The data was transferred to Google Colab for further exploration. Using pandas library, we confirmed there was no missing data.
Duplicate Check: Twelve duplicates were identified, but upon inspection and verification with the data dictionary, these entries were confirmed as unique responses due to unique IDs.
Visualization Tool Selection: Since the data required no adjustments, it was directly imported into Power BI for dashboard creation and analysis.
## Design Inspiration

Before building visualizations, a brief exploration of existing human resources dashboards was conducted to gather inspiration for color schemes and design aesthetics. A dark-themed, minimalist design was chosen as a reference point.

## Project Objectives

The project aimed to achieve two primary objectives:

Answer the ten pre-defined survey questions related to employee satisfaction:
Generate additional insights from the data beyond the pre-defined questions.
## Data Preprocessing

Calculating Overall Satisfaction: A new calculated field was created to represent overall employee satisfaction by averaging responses from relevant questions.
Identifying Happiest Departments and Roles: Charts were planned to identify the departments and roles with the highest satisfaction scores.
Encoding Conversion: To answer a question regarding roles (potentially question 2), the one-hot encoded fields for roles were transformed into a single calculated field named "Role."
## Visualization and Insights

During the visualization stage, it was discovered that question 7 was duplicated. The responses were merged to create an accurate representation.

The following visualizations were created:

Response Ratio by Question: This chart displayed the overall response rate for each survey question.
Response Ratio by Role: This chart explored response variations across different employee roles.
Response Ratio by Department: This chart analyzed response patterns within different departments.
These visualizations were used to derive insights into employee sentiment and satisfaction across various aspects of the work experience.

## Conclusion

This data analysis project successfully utilized Visualization tools to generate visualizations that answered the pre-defined questions and provided additional insights into employee satisfaction. By exploring different aspects of the data, the project revealed valuable information regarding employee needs and areas for improvement within the organization.

# Project 2: Restaurant Analytics

## Project Overview

This section details the data exploration and initial visualization approach for the second capstone project, focusing on restaurant analytics.

## Data Inspection

The data exploration began with manually scrolling through the data to assess the need for cleaning.

## Data Cleaning Decisions

The decision was made to proceed with visualization without extensive cleaning. Missing data points will be represented as null values and potentially dropped during analysis if necessary.

##  Visualization Strategy

The initial visualizations will target the answer pre-defined questions using charts.

## Dashboard Design

To facilitate answering all questions effectively, the dashboards will be divided into two sections:

Consumer Profile: This section will focus on visualizing data related to customer demographics and behavior.
Restaurant Profile: This section will explore data pertaining to restaurant performance metrics.
## Data Mapping

Since the data was deemed clean, the focus shifted towards mapping the fact and dimension tables within the chosen visualization tool.


# Project 3: Global Store Analysis

## Project Overview

This section details the approach taken for the third capstone project, analyzing data from a global store chain.

## Analysis Approach

The project focused primarily on data visualization. The goal was to utilize visualizations to answer all seven pre-defined questions related to the global store's performance.

## Data Exploration

A detailed exploration of the data was not explicitly done outside of visualizing tools. 

## Visualization Strategy

The project relied heavily on visualizations to answer the questions. The specific types of charts used would depend on the nature of the questions and the data available.

## Analysis and Insights

The primary focus was on using the created visualizations to extract insights and answer the pre-defined questions concerning the global store's performance.


# Conclusion (All Projects)

These capstone projects demonstrate the power of data visualization in extracting valuable insights from data. By effectively using visualizations, you can answer questions, identify trends, and gain a deeper understanding of complex datasets.

##Link to Dashboards
https://drive.google.com/drive/folders/1LAERIDFph7kw708tCRApuwDg0eS6whBl?usp=sharing
