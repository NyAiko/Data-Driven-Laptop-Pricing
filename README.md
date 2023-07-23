## Overview

Welcome to "Data Driven Laptop Pricing" where we embark on an exciting journey to predict laptop prices using cutting-edge data science techniques. Our [dataset](https://www.kaggle.com/datasets/dharmik34/laptop-price-prediction), sourced from [Kaggle](https://www.kaggle.com), serves as the foundation for our exploration. Our project revolves around three primary objectives:

1. **Unraveling Laptop Price Dynamics:** Our foremost goal is to gain a comprehensive understanding of how laptop prices operate and what factors significantly influence their pricing.

2. **Factor Analysis for Pricing:** By conducting a thorough analysis, we aim to identify the key factors that play a pivotal role in determining laptop prices.

3. **Regression Modeling Mastery:** Armed with powerful data science tools, we set out to construct an accurate and robust regression model that can precisely predict laptop prices based on essential features.

## Tools and Libraries

For our daring expedition, we have assembled an impressive array of data science tools and libraries:

- **Python:** The heart and soul of our project, providing us the platform for executing our data science magic.

- **Numpy:** A trusty companion in numerical computations, simplifying complex operations.

- **Pandas:** A versatile data manipulation library that ensures our dataset is primed and ready for analysis.

- **Matplotlib and Seaborn:** Our visualization wizards, allowing us to unveil mesmerizing patterns hidden within the data.

- **Scikit-Learn:** Our guiding light in building Machine Learning models.

## Data Processing

In our quest for truth, the first step is to process the data meticulously. Our data processing endeavors include:

- **Cleansing Numeric Values:** Utilizing the power of Python's lambda functions, we rid our numerical features of any non-numeric clutter, such as GB, st, nd, rd, th, and more.
- **Remove redundant features:** Including the laptop's operating system. For instance, it's evident that most computers come with Windows OS, while only Apple boasts MacOS.

## Exploratory Data Analysis (EDA)

As true data explorers, we embark on the EDA phase, where we unlock the secrets hidden within the dataset. Visualizations become our compass, guiding us to uncover valuable patterns and insights.


![eda1]('https://github.com/NyAiko/Data-Driven-Laptop-Pricing/blob/master/images/proc.png')
![eda2]('https://github.com/NyAiko/Data-Driven-Laptop-Pricing/blob/master/images/proc_gnrtn.png')
![eda3]('https://github.com/NyAiko/Data-Driven-Laptop-Pricing/blob/master/images/ram.png')
![eda0]('https://github.com/NyAiko/Data-Driven-Laptop-Pricing/blob/master/images/corr.png')


## Machine Learning Model

We are going to train a Ridge Regression. To preserve the integrity of our results, we utilize Scikit-Learn pipelines, guarding against "Data Leakage" and ensuring accurate predictions. The learning curves provide assurance that our model doesn't overfit the training set. By harnessing the power of GridSearchCV, we uncover the optimal L2 regularization coefficient. The model has R2 score about 75% on the unseen data.

## Conclusion

In conclusion, "Data Driven Laptop Pricing" stands as a testament to the potential of data science in deciphering the intricacies of laptop pricing. Through our journey, we have gained valuable insights into laptop price dynamics and the key factors shaping their values. Our formidable Ridge Regression model empowers us to predict prices with remarkable accuracy.This project sparks a new era of informed decisions in the world of laptops, offering benefits to consumers, manufacturers, and the data science community.
