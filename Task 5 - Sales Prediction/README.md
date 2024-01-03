**The task**
Sales Prediction using Python

Sales prediction means predicting how much of a product people will buy based on factors
such as the amount you spend to advertise your product, the segment of people you
advertise for, or the platform you are advertising on about your product.

Typically, a product and service-based business always need their Data Scientist to predict
their future sales with every step they take to manipulate the cost of advertising their
product. So let’s start the task of sales prediction with machine learning using Python.

**The report of the prediction**

Sales Prediction Analysis Report


The aim of this analysis was to predict sales based on advertising budgets across three different media channels: TV, Radio, and Newspaper. This is crucial for making informed marketing decisions and optimizing budget allocation.

**Data Overview**

The dataset consisted of 200 entries, each detailing advertising budgets for TV, Radio, and Newspaper, along with corresponding sales figures.

**Analysis Steps**

**Data Loading and Exploration and preprocessing**
The dataset was loaded and examined. It contained no missing values but had two outliers in the Newspaper column. However, the outliers was left intact.

**Feature Analysis**
Scatter plots and a correlation matrix were used to analyze the relationships between each advertising medium and sales.

Findings indicated that TV and Radio had a stronger positive correlation with sales compared to Newspaper.

**Model Selection and Training**
A Linear Regression model was chosen for its ability to quantify the impact of each advertising medium on sales.

The model was trained using an 80-20 split for training and testing data.

**Model Evaluation**
The model showed a Mean Squared Error (MSE) of approximately 3.17 and an R-squared value of 0.90, indicating a high level of accuracy in predicting sales.

**Impact Analysis and Specific Prediction**
The model’s coefficients were analyzed to understand the impact of each medium on sales.

A specific prediction was made for a hypothetical advertising budget allocation.

**Key Findings**
**Advertising Effectiveness:** TV and Radio advertising budgets had a more significant impact on sales compared to Newspaper.

**Sales Prediction:** For the example budgets (TV: $150k, Radio: $25k, Newspaper: $20k), the model predicted sales of approximately 14.47 thousand units.

**Budget Allocation:** The analysis suggests that allocating more budget to TV and Radio advertising could be more effective in driving sales.


This analysis provides valuable insights into the effectiveness of different advertising mediums on sales. 