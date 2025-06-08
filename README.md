# Restaurant-tips-Analysys
## 1. Introduction
This project aims to use the restaurant tips dataset to practice creating composition plots and visualizations. We will examine the relationship between different variables and the tips given.

![image](https://github.com/user-attachments/assets/9f6b43cd-60c9-446a-af9a-f6b7b375d419)

## 2. Data Description
### 2.1  Data Source
Dataset: https://raw.githubusercontent.com/RusAbk/sca_datasets/main/tips.csv
### 2.2 Dataset Overview
- Format: CSV
- Rows: 244
- Columns: 8
- Key Columns: `id`, `total_bill`, `tip`, `sex`, `smoker`, `day`, `time`, `size`
### 2.3 How to Access the Data
This project runs on Google Colab, and the dataset is loaded directly using Python. No manual download is needed.

In the notebook, the data is loaded with the following command:

import pandas as pd

url = "https://raw.githubusercontent.com/RusAbk/sca_datasets/main/tips.csv"

df = pd.read_csv(url)

Just run the code cell, and the dataset will be fetched automatically from GitHub.

## 3. Main Goals
- Investigate the relationship between tip amount and total bill.
- Analyze tipping behavior by gender and smoking status.
- Explore the impact of time of day and day of the week on tipping.
- Visualize patterns and generate statistical insights.

## 4. Key result 

- Tips increase with the total bill, but not linearly.
- Male customers tend to tip slightly more on average.
- Smokers show different tipping behavior depending on the day.
- Dinner has higher total bills and tips compared to lunch.

Below is the table of descriptive statistics for the dataset.

![image](https://github.com/user-attachments/assets/ef714ac5-ef91-4492-ac73-140bb18ad402)

The table summarizes basic descriptive statistics, including count, mean, standard deviation, percentiles, minimum, and maximum values for the variables id, total_bill, tip, and size.

## 5. Notebooks
https://colab.research.google.com/drive/1pWmycrcTBt1A8nz_dduhDdMyz3KKNq3i#scrollTo=VTMgbIIxG19C:  Main notebook for data exploration, visualization, and insights.

