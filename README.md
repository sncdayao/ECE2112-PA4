# **ECE2112 - Programming Assignment 4**
# **Experiment 4: Data Wrangling and Data Visualization**

## Getting Started
In this repository, you will find my codes for Experiment 4 containing the **ECE BOARD EXAM PROBLEM**
#### Problem 1
- Create the following data frames based on the format provided: <br>
  Example: Vis = [“Name”, “Gender”, “Track”, “Math<70”]; hometown is constant as Visayas <br>

Output:<br>
![Screenshot 2024-09-17 180004](https://github.com/user-attachments/assets/6e2c5e0a-d4a9-4182-95d6-2704a6c82c25)
  - Filename: Instru = [“Name”, “GEAS”, “Electronics >70”]; where track is constant as Instrumentation and hometown Luzon
  - Filename: Mindy = [ “Name”, “Track”, “Electronics”, “Average >=55”]; where hometown is constant as Mindanao and gender Female

#### Problem 2
- Create a visualization that shows how the different features contributes to average grade. Does chosen track in college, gender, or hometown contributes to a higher average score? <br>
<br>

The following software and libraries were used in the completion of this experiment:
- Anaconda Navigator 2.6.0<br>
- Jupyter Notebook 7.0.8
- pandas (Python Data Analysis) library
- Matplotlib library

## File Inclusions
1. **PA4 - Dayao.ipynb** - Jupyter Notebook containing code for ECE Board Exam Problem
2. **board.xlsx** - given ECE Board Exam data

## Problem 1
This problem involves creating multiple data frames from a provided dataset in .xlsx format using the ***pd.read_excel('board2.xlsx')*** operation. The task was to organize and filter data based on given conditions such as gender, track, and acquired scores from the ECE Board Exam. The specific parameters were applied to each data frame using the ***.loc*** operation.
- **Instru Data Frame**: This data frame filters the students by "Name", "GEAS", and "Electronics>70". The track is fixed to Instrumentation, and the hometown is set to "Luzon". This identifies the exam takers whose hometown is Luzon, college track is Instrumentation, and acquired an Electronics score that is greater than 70, while displaying their name and GEAS score.
- **Mindy Data Frame**: This data frame sorts students according to "Name", "Track", and "Electronics", where "Average>=55". The hometown is fixed as "Mindanao", and the gender is set to "Female". This locates the exam takers whose average grade is at least 55, from Mindanao, and are Female, while displaying their name, track, and Electronics score.

## Problem 2
This problem involves creating a visualization to show how different factors contribute to students' average grades. The visualization compared the influence of the chosen track, gender, and hometown on the average score. A bar graph was used to separately analyze the average score by track, gender, and hometown, using the Matplotlib operations ***.groupby*** and ***.plot***.

## Authors
Sophia Nicole C. Dayao
<br>
2ECE-C
