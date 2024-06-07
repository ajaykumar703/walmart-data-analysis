# Walmart Black Friday Purchase Behavior Analysis

## Project Overview

The objective of this project is to analyze customer purchase behavior at Walmart during Black Friday, with a particular focus on understanding if there are differences in spending habits between male and female customers. By examining various factors such as age, occupation, city category, and marital status, the goal is to provide actionable insights to the management team for better business decision-making.

## Dataset

The dataset contains transactional data of customers who made purchases at Walmart during Black Friday. It includes the following features:

- **User_ID**: Unique identifier for each customer.
- **Product_ID**: Unique identifier for each product.
- **Gender**: Gender of the customer (Male/Female).
- **Age**: Age group of the customer (categorized in bins).
- **Occupation**: Masked occupation identifier of the customer.
- **City_Category**: Category of the city where the customer resides (A, B, C).
- **StayInCurrentCityYears**: Number of years the customer has stayed in the current city.
- **Marital_Status**: Marital status of the customer.
- **ProductCategory**: Masked product category identifier.
- **Purchase**: Purchase amount spent by the customer.

## Key Questions

1. Do women spend more on Black Friday than men?
2. How do various factors such as age, occupation, city category, and marital status influence the purchase amount?

## Analysis

To address the key questions, the following analyses will be performed:

1. **Gender-based Spending Analysis**: Compare the average purchase amounts between male and female customers.
2. **Age-wise Spending Analysis**: Investigate how spending varies across different age groups.
3. **Occupation-wise Spending Analysis**: Examine the influence of occupation on purchase behavior.
4. **City Category-wise Spending Analysis**: Analyze spending patterns across different city categories (A, B, C).
5. **Marital Status-wise Spending Analysis**: Assess how marital status impacts purchase amounts.
6. **Correlation Analysis**: Explore correlations between different factors and the purchase amount.

## Tools and Technologies

- **Python**: For data analysis and visualization.
- **Pandas**: For data manipulation and analysis.
- **Matplotlib/Seaborn**: For data visualization.
- **Jupyter Notebook**: For interactive data analysis.

  # Steps to Run the Analysis

## 1. Clone the Repository

Clone this repository to your local machine.
```sh
git clone https://github.com/yourusername/WalmartBlackFridayAnalysis.git
```

## 2. Install Dependencies

Install the required Python libraries.
```sh
pip install pandas matplotlib seaborn jupyter
```

## 3. Download Dataset

Download the dataset from the provided link and place it in the repository folder.

## 4. Run the Jupyter Notebook


```sh
jupyter notebook WalmartBlackFridayAnalysis.ipynb
```
Save this content in a file named `steps_to_run.md` in your project repository.
