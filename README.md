# Remote Work - A Stack Overflow Survey Analysis
This repository consists of an anaylsis undertaken to better understand the experience around Remote Work for developers. To read more the findings please [checkout the associated medium article.](https://medium.com/@Arunn_AT/remote-work-the-new-norm-5d9beb956a85)

## Data

The data used is the [Annual Developer Survey](https://insights.stackoverflow.com/survey) collected by Stackoverflow for the year 2019 (latest available). It contains responses of nearly 90,000 participants from over 170 countries and dependent territories. According to [Stack Overflow](https://stackoverflow.com/), 2019 Annual Developer Survey examines all aspects of the developer experience from career satisfaction and job search to education and opinions on open source software.

To get started please download the data (~200MB) from [here](https://drive.google.com/open?id=1QOmVDpd8hcVYqqUXDXf68UMDWQZP0wQV) and add it under 'data/' directory.

## Pre-requisites

The project was developed using python 3.6.7 with the following packages.
- Pandas
- Numpy
- Matplotlib
- Seaborn

Installation with pip:

```bash
pip install -r requirements.txt
```
## Files
- AnalysisReport.ipynb : Jupyter Notebook with all the workings including data preparation, analysis and findings.
- requirements.txt : pre-requiste libraries for the project
- ouput/ : images from Data Visualization

## Project Motivation

The questions answered regarding remote work through data in the analysis are
1. Are developers who work remotely more satisfied with the job?
2. Do remote workers earn more?
3. In what type of organisations are remote work popular?
4. What are the most common challenges faced when working remotely?

## Summary
This project employed CRISP-DM, a popular methodology for solving data science problems. Business Questions were raised and and an understanding of the data was achieved in the beginning. The data was prepared for the relevant questions, and throughly analysed to obtain findings. The findings were validated and the results were communicated in the form of an [blog post.](https://medium.com/@Arunn_AT/remote-work-the-new-norm-5d9beb956a85)

## Acknowledgements

[Stack Overflow](https://stackoverflow.com/), for collecting, cleaning and providing the data for analysis.


