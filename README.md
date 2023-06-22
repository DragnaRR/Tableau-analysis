
# Tableau
Tableau is a visual analytics platform used in the Business Intelligence Industry.  It helps in simplifying raw data in a very easily understandable format. Also presenting the data that can be understood by professionals at any level in an organization. It also allows non-technical users to create customized dashboards. Makeing Data analysis very fast and create visualizations in the form of dashboards and worksheets. 

It is crafted in a way that all kinds of plots, charts and graphs can be positioned simultaneously for visualization. Providing a highly interactive and intuitive visual-based exploration experience for business users to easily access, prepare and analyze their data without the need for coding.





## Customer Analysis
Customer analysis is the practice of using qualitative and quantitative data to gain insight into the customers. The goal is to understand their needs, points, and objectives. At the same time, customer analysis helps us understand what drives people to make a purchase, how and when these purchases happen, the frequency of these purchases, and other relevant information.

[link to the dataset](https://www.kaggle.com/datasets/saileshedara/customer-analysis)

- #### Total revenue as per state
![revenue](https://github.com/DragnaRR/Tableau-analysis/assets/95096810/0129f13f-9a08-4e5d-ba4b-56aa1defed5d)

- #### Total revenue per month
![Revenue](https://github.com/DragnaRR/Tableau-analysis/blob/main/screenshots/revenue_mon.PNG)

- #### Total revenue based on age group
![Revenue](https://github.com/DragnaRR/Tableau-analysis/blob/main/screenshots/revenue_age.PNG)

- #### Quantity discount correlation
![discount_corr](https://github.com/DragnaRR/Tableau-analysis/blob/main/screenshots/discount_correlation.PNG)

- #### Total revenue percentage as per region
![revenue](https://github.com/DragnaRR/Tableau-analysis/blob/main/screenshots/revenue_region.PNG)

- #### Revenue based on category and gender
![revenue](https://github.com/DragnaRR/Tableau-analysis/blob/main/screenshots/revenue_gender.PNG)
##### calculated field: Female revenue
```
IF [Gender] = 'F' THEN [Total]
END
```
##### calculated field: Male revenue
```
IF [Gender] = 'M' THEN [Total]
END
```
##### calculated field: axis
```
0
```
- #### Customer Analysis Dashboard
![customer](https://github.com/DragnaRR/Tableau-analysis/blob/main/screenshots/customer.PNG)

## Product Sales Analysis
A product sales analysis is a detailed report that shows a business's sales performance, as well as customer data and generated revenue. The report defines the strengths and weaknesses of products and sales teams by referencing historical and current metrics to detect emerging trends that are most relevant to a company.

- #### Product sales
![product sales](https://github.com/DragnaRR/Tableau-analysis/blob/main/screenshots/product_sales.PNG)

- #### Average sales
![avg sales](https://github.com/DragnaRR/Tableau-analysis/blob/main/screenshots/avg_sales.PNG)

- #### Product category chart
![category chart](https://github.com/DragnaRR/Tableau-analysis/blob/main/screenshots/product%20category%20chart.PNG)

- #### Product sales analysis
![product sales analysis](https://github.com/DragnaRR/Tableau-analysis/assets/95096810/edc70ff6-3647-413c-b4fc-05770416b8ab)


## Covid-19 Scatter plot
![covid](https://github.com/DragnaRR/Tableau-analysis/assets/95096810/1399e842-fd09-49a6-b9e3-06bf3472d724)
