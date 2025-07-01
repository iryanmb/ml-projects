# Ecommerce Client Spend Prediction
This project develops a linear regression model to predict yearly customer spending based on user behavior data from an e-commerce clothing company. The business wants to understand whether to prioritize improving their mobile app or their website to drive revenue growth. By exploring key variables like time on app, website usage, and membership duration, the model aims to support data-driven strategy decisions.

## Dataset Overview
Each row represents a customer and includes:

`Avg. Session Length`: Average time spent in an in-store personal stylist session  
`Time on App`: Time (in minutes) spent using the mobile app  
`Time on Website`: Time (in minutes) spent on the website  
`Length of Membership`: Number of years the customer has been a member  
`Yearly Amount Spent`: Annual dollar amount spent (target variable)  


Additional features like 'Email', 'Address', and 'Avatar' were excluded from modeling due to being non-numeric and/or high-cardinality.

## Key Insights
- Length of Membership and Time on App are the strongest predictors of customer spending

- Time on Website has little to no linear relationship with yearly spending

- The model performs well, with low error metrics and residuals close to a normal distribution

## Technologies Used
- Python (Pandas, NumPy, Scikit-learn)

- Jupyter Notebook

- Seaborn & Matplotlib for visualization