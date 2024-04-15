# Big Mart Sales Data Prediction

This project aims to perform Exploratory Data Analysis (EDA) on the Big Mart sales dataset using Python's Pandas, visualization, and scikit-learn libraries. The main goal is to gain insights into the dataset and understand the factors influencing the sales of items in Big Mart outlets.

## Project Overview

The dataset contains information about various attributes related to the sales of items in Big Mart outlets. These attributes include item weight, fat content, visibility, item type, MRP (Maximum Retail Price), outlet size, outlet type, establishment year, and outlet sales.

## Dataset Description

- **Item_Identifier**: Unique code for each item/product
- **Item_Weight**: Weight of the items
- **Item_Fat_Content**: Describes the fat content in the item (e.g., Low Fat, Regular)
- **Item_Visibility**: The percentage of the total display area allocated to the particular product
- **Item_Type**: Category of the items (e.g., meat, fruit, dairy)
- **Item_MRP**: Price of the items
- **Outlet_Identifier**: Unique outlet code
- **Outlet_Establishment_Year**: The year the outlet was established
- **Outlet_Size**: Outlet size (categorical: Small, Medium, High)
- **Outlet_Location_Type**: Outlet location type (tier 1, tier 2, tier 3)
- **Outlet_Type**: Outlet type (e.g., supermarket, grocery store)
- **Item_Outlet_Sales**: Outlet sales of the product

## Project Goals

1. Data Cleaning: Identify and handle null values, remove duplicates, and fix structural errors in the dataset.
2. Demonstrate the effect of attributes on the target variable (Item_Outlet_Sales) through univariate and bivariate analysis.
3. Perform statistical analysis to understand the distribution of variables and their relationships.
4. Visualize the data using appropriate plots and charts.
5. Gain insights from the analysis to inform business decisions and strategies.

## Insights from EDA

### Bivariate Analysis

- **Fat_Content_Type**: Item weight does not significantly impact item sales. Both fat content types have similar visibility, with some items having higher visibility but lower sales. Low-fat products tend to have higher prices.
- **Item_Type**: Item weight does not significantly impact item sales.
- **Outlet_Size**: Outlets with small sizes have evenly distributed item visibility and higher sales.
- **Outlet_Type**: Supermarket Type 3 shows increased sales with increasing MRP compared to Supermarket Type 1 and grocery stores. Despite higher visibility, grocery stores have lower sales.

### Univariate Analysis

- Low-fat items have lower sales compared to regular items.
- Seafood is one of the highest-selling product types.
- Outlets established in 1985 have the highest sales, while those established in 1998 have the lowest.
- Outlet size does not significantly affect sales, but smaller outlets tend to have higher sales.
- Tier 3 store locations have the highest sales, while tier 2 has the lowest.
- Grocery stores have the lowest sales, while Supermarket Type 3 has the highest.

## Conclusion

The analysis provides valuable insights into the factors influencing Big Mart sales, which can inform marketing, pricing, and inventory management strategies to optimize sales and revenue.

Feel free to explore the Jupyter Notebook for detailed analysis and visualization of the dataset.
