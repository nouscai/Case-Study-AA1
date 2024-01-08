# Case Study: Predicting E-commerce Coupon Use (Case-Study-AA1)

## Overview

This project aims to examine the influence of coupons on consumer purchasing behavior within the e-commerce sector. Utilizing a comprehensive dataset from Kaggle, specifically designed for marketing insights in e-commerce. https://www.kaggle.com/datasets/rishikumarrajvansh/marketing-insights-for-e-commerce-company/data?select=Online_Sales.csv, the study will delve into various aspects of online sales data. The selection of this dataset is anchored on the premise that coupons are a proven tool for stimulating consumer purchases.

## Objectives

The primary objective is to conduct an in-depth exploratory analysis with a special focus on the role of coupons in shaping consumer buying patterns. The study will leverage the rich data structure provided in the dataset, employing a range of statistical methods and data visualization techniques. This approach aims to elucidate the intricate relationship between coupon usage and sales figures.

## Methodology

1. **Data Integration (Tool: Talend Data Integration):** This phase involves merging different datasets to enhance the clarity and cleanliness of the data structure. It's crucial for establishing a solid foundation for subsequent analyses.

2. **Data Transformation and Processing (Tool: KNIME):** Given the limitation of Talend Data Prep's free version (max 30,000 records), KNIME steps in as an alternative for data transformation and processing. This step includes checking for null values and converting data types to improve modeling efficiency. Specifically, it entails transforming the representation of coupons into a binary classification (0 and 1).

3. **Data Analysis and Model Evaluation (Tool: SAS e-Miner):** In this stage, the focus shifts to exploring relationships within the dataset. This includes identifying connections between various variables and assessing the effectiveness of predictive models.

## Expected Outcomes

The analyses conducted in this project are anticipated to provide a deeper understanding of the impact of coupons on e-commerce sales. The insights gained could be instrumental in shaping effective e-commerce marketing strategies, especially in the context of enhancing sales through targeted coupon distribution.

Sure, here's the translation in Markdown format:


# Learning Reflections and Challenges

## 1. Repetitiveness in Dataset Exploration
At this stage, my perception of the dataset becomes clearer through exploration. For instance, initially, the dataset had issues; it lacked an accurate ID. CustomerID and TransactionID are not actual IDs for this dataset, as they both contain non-overlapping duplicates. However, I wasn't fully aware of this issue at the start. But during my exploration with SAS, I continually identified problems, although the results of this modeling were still unsatisfactory. Nevertheless, I've understood the process of exploring datasets, a process that may require repetition and may need me to seek solutions from the dataset itself or from the model.

## 2. Use of Multiple Software Tools
Initially, I didn't understand why we needed these tools, and due to my lack of familiarity with them, I was more fearful of using them. However, during my exploration, I realized that these software tools are often used in combination.
Data Integration software is very powerful and offers visualization capabilities. (Due to my unfamiliarity, I replaced some of its functions with Python in the case study.) But as I used it, I found that Python coding requires reverse thinking – thinking about what I want to become and then processing, whereas Data Integration is about forward-thinking in processing software, making it a very useful tool. It allows for convenient transformations of columns and even lets me convert my files from xlsm to csv for standardized transformations.
KNIME: Since my dataset exceeded 30,000 rows, I couldn't use it in Data Preparation, so I turned to KNIME. I believe its interface and functions for viewing data are quite similar to Data Integration and can be used interchangeably. This helps me understand each column better and make basic judgments.
SAS: SAS software is rich in features. For example, functions available in KNIME for imputing values are also available in SAS. However, since my dataset had no missing values, I didn't use this feature. The exploration in SAS helped me understand the overall situation of my dataset, whether it had significant correlations or not.

## 3. Reflection
I think this learning exploration was very meaningful. Previous studies always provided datasets, which were classic datasets. This time, the teacher let us find our datasets using a data structure, allowing me to experience the real process of a project exploration. I think if I become a data scientist in the future, I won't always encounter results with 90% accuracy. Instead, it will be like this time where, firstly, a target of 1 couldn't be detected in the model due to its small quantity. Then, there was the issue of ineffective model adjustments. This has raised higher demands on my knowledge structure and software use. This learning experience has made me start to think calmly about the challenges I will face in the future, and I should more solidly grasp and learn this knowledge and software. As a data scientist, a calm mind and proficient software skills are equally important.
I also encountered an issue during an exam where the SAS software crashed and wouldn't open, which made me think about how I would communicate with clients if such unexpected events happen in the future and how I would mitigate these risks.

Overall, this case study was invaluable to me, prompting me to reflect on my learning and enhancing my ability to face risks.
