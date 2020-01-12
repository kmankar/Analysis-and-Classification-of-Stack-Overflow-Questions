# Analysis-and-Classification-of-Stack-Overflow-Questions

## For Python Version 3

## Dataset
The data set was obtained from BigQuery (Stack Overflow database). The Stack Overflow database contains multiple tables 
like badges, comments etc. Our primary data set  includes columns - title, body, tags and view_count from the post_questions table. 
The table originally contains 18154493 records, but for this project we have chosen 7500 records due to memory and processing constraints.

## Description

**There exists 1 Script that:**
- Connects to Bigquery
- Extracts records
- Imports required libraries
- Performs Feature Engineering
- Performs Exploratory Data Analysis
- Performs Predictive Analytics

**Instructions to run the Python File**:
1. Follow the steps mentioned in the word document named : "Steps to query Stack Overflow data from BigQuery and Jupyter Notebook". 
2. Open final file in Jupyter Notebbok 
3. Run the program
4. Once run, accuarcy will be generated for every method used.

## Result and Model summaries
Using feature engineering and natural language processing techniques: We were able to classify the questions from Stack Overflow based on the titles and their content with an accuracy of 82%. These results were achieved using Neural Network in conjunction with the extracted features from the code blocks of the text.

| Model | Accuracy | Precision | Recall | F1-Score | Support |
|---|---|---|---|---|---|
| Neural Network | 0.82 | 0.82 | 0.82 | 0.82 | 1752 |
| Naive Bayes | 0.70 |0.79 |0.70 | -0.64 | 1273 |

