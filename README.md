# Data-606-Capstone-Project

# ETL Pipeline for data warehousing


## Introduction
Big Data in Healthcare could reduce treatment costs, forecast disease outbreaks, assist clinicians in better and faster managing processes and obtaining results, and improve overall medical quality. In the healthcare industry, dozens of companies have already employed big data: clinic documents and archives, health records such as lab test results, health history, allergies, and so on, and IoT healthcare equipment.

Big Data is a strong tool that supports healthcare providers in making optimal clinical decisions and delivers detailed analytics based on massive amounts of stored data. One issue is that the data is aggregated, so it rarely fits into an organization's hierarchical framework or is represented in a pre-defined way.


### Motivation
As we all know, data is unstructured in order to be more flexible to a wide range of formats. In most cases, organized framework input options (such as checkboxes, drop-down menu selections, and radio buttons) fall short of appropriately framing and appropriating data, resulting in unstructured data that can be altered to work with them retroactively. To that aim, data of various types can only be recorded in unstructured formats. Consider how difficult it would be to compile important but disparate data about a patient's preferences, clinical particulate, lifestyle and socioeconomic factors, and a plethora of other patient-specific informational components into a unified and intuitive data format that could then be analyzed by various algorithms to help determine the best course of patient care.


### Data
This project's dataset is a relational set of files from National Plan and Provider Enumeration System describing prescribed drug practioners in different states. The collection is anonymized and includes over 24 million prescription transactions and purchases for over 2779 different drugs. For each prescribed practioner, information about 4 to 100 of their orders is provided, along with transaction id and other meta data for each order. The state and city of the order placed are also accessible, as is a relative measure of time between orders. The dataset is available for non-commercial use only 

City Dimension File - https://prescpipeline.blob.core.windows.net/input-vendor-data/city/us_cities_dimension.parquet?st=2022-04-21T14:19:25Z&se=2022-12-31T22:19:25Z&si=read&spr=https&sv=2020-08-04&sr=c&sig=wjY0KtPvyy%2BbIpopBqMKAGmmSHsSvLhqL0n%2BBGFVXOQ%3D

Prescriber Fact File - https://prescpipeline.blob.core.windows.net/input-vendor-data/presc/USA_Presc_Medicare_Data_2021.csv?st=2022-04-21T14:19:25Z&se=2022-12-31T22:19:25Z&si=read&spr=https&sv=2020-08-04&sr=c&sig=wjY0KtPvyy%2BbIpopBqMKAGmmSHsSvLhqL0n%2BBGFVXOQ%3D


### Business Understanding
Some of the questions I want to answer are:
- Predict cost of drugs in various states and best drug practioners.

- Predict which state has the maximum sales and most consumed drug.


### Medthodology
Initially, I plan to delve deep into the data to gain a complete understanding of the many variables. I intend to do some data wrangling and cleaning to cope with missing values and other issues. Once the data has been cleansed, I plan to perform exploratory analysis to extract any intriguing insights from it. Feature engineering will also be used to uncover new significant features that may be employed in the model construction process. Finally, various models will be created using machine learning methods. Data visualizations will support in the communication of these findings and will help to tell a story.

<img>https://github.com/princecj65779/abc/blob/main/Copy%20of%20Copy%20of%2023andMe%20Genomics.png<img/>
