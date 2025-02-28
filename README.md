![banner](assets/Banner_Olympics_Dataset.png)
Banner [source](https://graphicsprings.com/blog/view/olympic-logo/)

![Microsoft Excel](https://img.shields.io/badge/Microsoft_Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)

Badge [source](https://shields.io/)

# Key findings: Olympics Dataset (Beijing 2022 and Tokyo 2020): Type, Discpline, Medal Count, Slicer

<!-- Authors -->
<!-- ## Reference
- Learn 80% of Data Analysis in Excel in Just 12 Minutes ( https://www.youtube.com/watch?v=O1QfG5SXRkM) -->

## Table of Contents

  - [Olympics Dataset (Beijing 2022 and Tokyo 2020): Type, Discpline, Medal Count, Slicer](#olympics-dataset-(beijing-2022-and-tokyo-2020):-type-discpline-medal-count-slicer)
  <!-- - [Reference](#reference) -->
  - [Table of Contents](#table-of-contents)
  - [Business Problem](#business-problem)
  - [Data source](#data-source)
  - [Methods](#methods) 
  - [Tech Stack](#tech-stack)
  - [Summary of Key Results](#summary-of-key-results)
  - [Lessons Learned and Recommendation](#lessons-learned-and-recommendation)
  - [Limitation and What Can Be Improved](#limitation-and-what-can-be-improved)
  - [Run Locally](#run-locally)

## Business Problem
This project focuses on key steps in the Data Analysis process: Cleaning, Transforming, Analyzing, and Visualizing data, using the Olympics Datasets from Tokyo 2020 and Beijing 2022.

The goal is to demonstrate how to work with real-world datasets by:

• Cleaning the data: removing duplicates and handling inconsistencies.

• Transforming the data: identifying and replacing specific terminologies to standardize the dataset.

• Analyzing the data: creating pivot tables to categorize by event type, discipline, and medals earned, as well as implementing slicers to group and filter results.

• Visualizing the results: generating charts to represent medal counts for better insights.

This workflow exemplifies the essential skills needed in Data Analysis, enabling more informed and insightful decisions based on data.

## Data Source

- Learn 80% of Data Analysis in Excel in Just 12 Minutes ( https://www.youtube.com/watch?v=O1QfG5SXRkM)

## Methods

- Data Cleaning
- Data Transformation
- Pivot Table Analysis
- Data Visualization 

## Tech Stack

- Microsoft Excel
    - Data Cleaning (Remove Duplicates)
    - Formulas & Functions
    - Pivot Tables
    - Filter
    - Charting & Data Visualization


## Summary of Key Results

Athlete vs. Team Participation Count

![Pivot Table - Athlete vs. Team Participation Count](assets/PivotTable_CountType_AthleteVsTeam.png)

Discipline Distribution with Count and Percentage

![Pivot Table - Discipline Distribution with Count and Percentage](assets/PivotTable_DisciplineDistributionCount_Percentage.png)

Olympic Medal Count by Country (Beijing 2022 & Tokyo 2020) with Game Filter

![Pivot Table - Olympic Medal Count by Country (Beijing 2022 & Tokyo 2020) with Game Filter](assets/PivotTable_OlympicMedalCountByCountry_GameFilter.png)

Stacked Chart Medal Count by Country (Gold, Silver, Bronze)

![Pivot Table - Stacked Chart Medal Count by Country (Gold, Silver, Bronze)](assets/PivotTable_StackedChartMedalCount_Country.png)

## Lessons Learned and Recommendation

- This project marked my first experience in visualizing and effectively communicating insights from a dataset by following key steps: Cleaning, Transforming, Analyzing, and Visualizing the data. I gained valuable skills in classifying data by discipline and using pivot tables to calculate counts and percentages. The process of transforming raw data into meaningful insights was a rewarding experience, helping me better understand the story behind the data and the importance of clear analysis.

- The recommended approach is to follow a structured method: clean the data by removing duplicates, transform it by standardizing terminologies, analyze it using pivot tables with slicers for better grouping, and finally, visualize the results with charts to simplify data interpretation. This step-by-step process makes understanding the dataset much easier.


## Limitation and What Can Be Improved

- Visualization: While Excel is a useful tool for data visualization, I believe there is potential for more polished and interactive visualizations by integrating specialized software such as Power BI or Tableau. I have yet to learn these platforms, but they could significantly enhance the visual appeal and interactivity of the data presentations. Exploring these tools would be a valuable next step for improving future analyses.

## Run Locally
Initialize git

```bash
git init
```


Clone the project

```bash
git clone https://github.com/johncanero/olympics_dataset_john_canero.git
```

enter the project directory

```bash
cd olympics_dataset_john_canero
```

Open in Visual Studio Code

```bash
code .
```

## Repository structure


```
├── assets
│   ├── Banner_Olympics_Dataset.png       
│   ├── PivotTable_CountType_AthleteVsTeam.png         
│   ├──PivotTable_DisciplineDistributionCount_Percentage.png              
│   ├── PivotTable_OlympicMedalCountByCountry_GameFilter.png  
│   ├── PivotTable_StackedChartMedalCount_Country.png          
│
|
├── 01_olympics_dataset_john_canero.xlsx
│ 
│
├── README.md                     
│
│
```
