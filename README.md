
# Tableau
Tableau is a visual analytics platform used in the Business Intelligence Industry.  It helps in simplifying raw data in a very easily understandable format. Also presenting the data that can be understood by professionals at any level in an organization. It also allows non-technical users to create customized dashboards. Makeing Data analysis very fast and create visualizations in the form of dashboards and worksheets. 

It is crafted in a way that all kinds of plots, charts and graphs can be positioned simultaneously for visualization. Providing a highly interactive and intuitive visual-based exploration experience for business users to easily access, prepare and analyze their data without the need for coding.





## Customer Analysis
Customer analysis is the practice of using qualitative and quantitative data to gain insight into the customers. The goal is to understand their needs, points, and objectives. At the same time, customer analysis helps us understand what drives people to make a purchase, how and when these purchases happen, the frequency of these purchases, and other relevant information.

[link to the dataset](https://www.kaggle.com/datasets/saileshedara/customer-analysis)

- #### Total revenue as per state
![Revenue](https://github.com/DragnaRR/Tableau-analysis/assets/95096810/0129f13f-9a08-4e5d-ba4b-56aa1defed5d)

- #### Total revenue per month
![Revenue](https://github.com/DragnaRR/Tableau-analysis/assets/95096810/76942bdf-6c48-4d91-bfbe-655b01811d18)

- #### Total revenue based on age group
![Revenue](https://github.com/DragnaRR/Tableau-analysis/assets/95096810/29634c36-689e-4118-8c53-6b40c64aa112)

- #### Quantity discount correlation
![discount_corr](https://github.com/DragnaRR/Tableau-analysis/assets/95096810/e60184af-a6dd-4751-93ad-0d2974009e31)

- #### Total revenue percentage as per region
![revenue](https://github.com/DragnaRR/Tableau-analysis/assets/95096810/4f3cafed-42ee-4aeb-84cb-994863aa60d1)

- #### Revenue based on category and gender
![revenue](https://github.com/DragnaRR/Tableau-analysis/assets/95096810/af9ec052-1831-452e-8851-5ec711916bf5)
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
![customer](https://github.com/DragnaRR/Tableau-analysis/assets/95096810/357a9ce3-1de2-4dbb-bff4-802afa0a1069)

## Product Sales Analysis
A product sales analysis is a detailed report that shows a business's sales performance, as well as customer data and generated revenue. The report defines the strengths and weaknesses of products and sales teams by referencing historical and current metrics to detect emerging trends that are most relevant to a company.

- #### Product sales
![product sales](https://github.com/DragnaRR/Tableau-analysis/blob/main/screenshots/product_sales.PNG)

- #### Average sales
![avg_sales](https://github.com/DragnaRR/Tableau-analysis/assets/95096810/8d551f59-819c-4a8c-a4c8-742dac145db6)

- #### Product category chart
![category chart](https://github.com/DragnaRR/Tableau-analysis/assets/95096810/8f9c550c-55da-4fc1-9723-4026ee8c7fa2)

- #### Product sales analysis
![product sales analysis](https://github.com/DragnaRR/Tableau-analysis/assets/95096810/edc70ff6-3647-413c-b4fc-05770416b8ab)


## Covid-19 Scatter plot
![covid](https://github.com/DragnaRR/Tableau-analysis/assets/95096810/1399e842-fd09-49a6-b9e3-06bf3472d724)
