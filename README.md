# Unicorns: An Exploratory Data Analysis of Billion-Dollar Startups
This project is an exploratory data analysis of the dataset based on [The CrunchBase Unicorn Board](https://news.crunchbase.com/unicorn-company-list/) released in 2022.

# Table of Contents
- [Author Information and Acknowledgements](https://github.com/ashleyjaye/unicorn_companies_exploratory_data_analysis/blob/main/README.md#author-information-and-acknowledgements)
- [Project Description](https://github.com/ashleyjaye/unicorn_companies_exploratory_data_analysis/blob/main/README.md#project-description)
- [The Task](https://github.com/ashleyjaye/unicorn_companies_exploratory_data_analysis/blob/main/README.md#the-task)
- [The Dataset](https://github.com/ashleyjaye/unicorn_companies_exploratory_data_analysis/blob/main/README.md#the-dataset)
- [The Process](https://github.com/ashleyjaye/unicorn_companies_exploratory_data_analysis/blob/main/README.md#the-process)
- [Used Technologies](https://github.com/ashleyjaye/unicorn_companies_exploratory_data_analysis/blob/main/README.md#used-technologies)
- [Disclaimer](https://github.com/ashleyjaye/unicorn_companies_exploratory_data_analysis/blob/main/README.md#disclaimer)

# Author Information and Acknowledgements
This project was created by [Ms. Ashley Jaye Milag](https://linktr.ee/mxashleyjaye) with support from **[FEMSTECH Worldwide e.V.](https://femstech.com/www.femstech.com/index.html)** and guidance from her instructor, [Mr. Alham O. Hotaki](https://www.linkedin.com/in/aohotaki/), an experienced professional data scientist and business analyst. 

# Project Description
Coined by Silicon Valley venture capitalist Aileen Lee in a 2013 TechCrunch article, **["Welcome To The Unicorn Club: Learning from Billion-Dollar Startups"](https://techcrunch.com/2013/11/02/welcome-to-the-unicorn-club/)**, the term **“unicorn”** refers to a privately held startup (a newly established business) valued at over 1 billion in U.S. dollars. Inspired by a mythical animal, it symbolizes the statistical rarity of successful ventures which made the term more popular in the venture capital industry. 

Unicorns are frequently found in sectors like technology, software, and financial services that demand substantial capital investment for product or service development and market entry. These companies typically boast large and rapidly expanding customer bases. Their focus on cutting-edge technologies and disruptive market trends enables them to attract substantial funding from venture capital and private equity investors. Since 2013, the number of unicorns has experienced a "meteoric" growth, surging from 39 companies in November 2013 to over 1,000+ companies in December 2022.

# The Task
The task was to conduct a structured exploration of the [unicorn companies’ dataset](https://github.com/ashleyjaye/unicorn_companies_exploratory_data_analysis/blob/main/unicorn_companies.csv) using a methodical approach called **exploratory data analysis** to assess data quality, detect anomalies and outliers, identify patterns and trends, leverage statistical techniques, and visualize data. 

A crucial component of exploratory data analysis is data visualization. This involves generating visual representations of data which include, but are not limited to, the following:
- Line Charts
- Bar Charts
- Pie Charts
- Heatmaps
- Scatter Plots
- Histograms
- Density Plots
- Box Plots
- Bubble Plots

# The Dataset
The dataset contains **1,074 data entries** (or rows) and **10 attributes** (or columns) which represent unicorn companies.

Here is a breakdown of the columns:

1. **Company:** Name of the unicorn company
2. **Valuation:** The company’s valuation in USD (as a string initially)
3. **Date Joined:** The date the company achieved its unicorn status
4. **Industry:** The classification based on the field the company operates in or the primary business activity the company engages in
5. **City:** The city of origin where the company is headquartered
6. **Country/Region:** The country or region of origin where the company is headquartered
7. **Continent:** The continent the company belongs to
8. **Year Founded:** The year the company was established (stored as an integer)
9. **Funding:** The total funding raised by the company in USD (as a string initially)
10. **Select Investors:** Key investors of the company

# The Process
The exploratory data analysis involved the following steps:
- **Step 1. Imports**: To import the necessary Python libraries (i.e., Pandas, NumPy, Matplotlib, and Seaborn) and the dataset to the Colab notebook.
- **Step 2. Data Exploration**: To inspect and explore the dataset.
- **Step 3. Handling Missing Values**: To detect, replace, and manage the missing values within the dataset.
- **Step 4: Data Cleaning**: To clean the data by arranging the values, fixing the rows and columns, and updating the unique values within the dataset.
- **Step 5: Statistics**: To show the descriptive statistics of the dataset, remove the outliers, and prepare the dataset for analysis and visualization.
- **Step 6: Visualized Exploration**: To analyze the dataset and generate the required visuals following the common techniques of exploratory data analysis such as univariate, bivariate, and multivariate analyses.
- **Step 7: Feature Engineering**: To transform the dataset by creating a new column and subsequently visualize its distribution.

# Used Technologies
The owner used the [Google Colaboratory](https://colab.research.google.com/) which hosts Jupyter (formerly iPython) Notebook for the exploratory data analysis. To properly document visualizations and summarize the findings, the owner created a report using [Google Docs](https://docs.google.com/). 

# Disclaimer

## Agreement 
No part of this project, except for the dataset (.csv) file, may be used, copied, reproduced, or distributed in any form or by any means without the prior written consent of the owner.

## Intended Purpose and Use
The content on this project does not, and is not intended to, provide professional, business, or legal advice; instead, all content, including information and materials available, are for general, educational, and informational purposes only. While every effort has been made to ensure relevance and accuracy of content, it may contain incomplete or outdated information. No representations or warranties, express or implied, are made regarding the availability, reliability, or suitability of the content.

## Views and Opinions
The views and opinions expressed are those of the owner and do not necessarily reflect the views or opinions of any entities they represent.

## Misuse and Liability
The owner disclaims all liability for any harm, loss, or damage resulting from the misuse or unlawful use of this content, including but are not limited to, unlawful activities or adverse effects of any kind.

## Comment Policy
While the owner does not discriminate against views or opinions posted, they reserve the right to disapprove or remove any comment. That comment will not be edited or modified to remove unacceptable content; it will simply be deleted. Some reasons include, but are not limited to, the following:
- Use of defamatory, libelous, demeaning, vulgar, obscene, abusive, racist, threatening, and/or harassing speech
- Use of offensive, explicit, and/or profane language
- Libel, slander, and/or personal attacks of any kind, including the use of offensive terms that target specific individuals or groups
- Spam, including content that promotes products, services, and/or gratuitous links or references
- Comments suggesting or encouraging illegal, dangerous, or destructive activity
- Other inappropriate and off-topic comments

## Third Party  
This project may contain reference links or materials from and to other third-party websites and platforms. Such links and materials are only for the convenience of the user, reader, or browser. Those third-party websites and platforms are out of the owner's control. In no event will the owner be responsible for any information linked to third-party websites and platforms and ability to use or inability to use them. Accessing such links is at your own risk and disclaims the owner from any liability for them.

## Amendments
The owner reserves the right to change or update this disclaimer at any time without notice. 



 
 
 
 


Copyright © 2025 Ashley Jaye Milag. All Rights Reserved.
