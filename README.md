# Layoff Prediction Using Financial Sentiment Analysis


*Uncovered and meticulously analyzed layoff data and AI used in technology companies, employing advanced Python techniques and data analysis methodologies, all within AI4ALL's cutting-edge AI4ALL Ignite accelerator.*


## Problem Statement

*As college students who enter the workforce soon, we want to know how the job market is faring as the boom of LLMs (e.g. ChatGPT) is a unique technological advancement we have not seen before.*

## Key Results 

*EXAMPLE:*
1. *Recorded over 1,000 data points and anlayzed the results*
2. *Identified two biases in data from layoffs.fyi*
   - Selection Bias
   - Platform/Source Bias


## Methodologies 



Key Features Used:
- GenAI Adoption Flag (Binary): Indicates if GenAI was adopted by the quarter
- Layoff History: 4-quarter rolling sum of layoffs (temporal context)
- Employee Sentiment: Polarity score (-1 to 1) from TextBlob analysis of reviews
- Neutral (0) for pre-adoption quarters or missing reviews
- Quarter Cyclical Encoding: 
- quarter_sin/quarter_cos for seasonal trends



## Data Sources

Kaggle Dataset: [Link to Kaggle Dataset](https://www.kaggle.com/datasets/tfisthis/enterprise-genai-adoption-and-workforce-impact-data)

Layoffs Dataset: [Link to Layoffs Dataset](https://layoffs.fyi/)

## Technologies Used 
(UPDATE IN README.md)
List the technologies, libraries, and frameworks used in your project.
- Python
- Pandas
- TensorFlow



## Authors

(UPDATE IN README.md)
List the names and contact information (e.g., email, GitHub profiles) of the authors or contributors.


*This project was completed in collaboration with:*
- *Rohit Chivukla ([abhi.chivukula@gmail.com
](abhi.chivukula@gmail.com
))*
- *Emma Hsieh ([eh5775@princeton.edu](mailto:eh5775@princeton.edu))*
