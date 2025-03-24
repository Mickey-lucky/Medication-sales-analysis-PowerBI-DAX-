# Medication-sales-analysis


## Introduction 
Project Overview: The project delved into medication sales datasets over the past several years. The dashboard explored sales data from 5 csv tables and extracted multi-faceted insights, product-wise, customer-wise and sales trend etc. The dashboard included multiple filter slicers, such as year, month, buyer type, country and parameters, such as top/bottom , TOPN . The performance KPIs are benchmarked against last month performance. [Project live report](https://app.powerbi.com/view?r=eyJrIjoiYjM1MzZlNWYtMmNjOS00N2U3LWJiODktYmVjODI5OGRjNzZhIiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9)



## Tools & Platform 
Power BI Desktop, CSV file, Dax Language, Power Query


## Key Steps:
1.	loaded data from CSV files to Power BI. Introduced 4 dimension tables (DrugLookup, CustomerTable, RegulatoryTable) and 1 fact sales tables
2.	Performed data cleaning and ETL in power query
3.	Bulit table relationship 
 
  ![Data model diagram!](https://github.com/user-attachments/assets/c2822d44-3a67-4b7e-b4fe-4246cfdafc19)<br><br>
4. Created dynamic measures, KPI & benchmark cards and parameters <br>

  ![Key measures!](https://github.com/user-attachments/assets/e8cb4587-b314-40a1-8320-dfd26caa9d6f)<br><br>
   
5. crafted product-wise, customer-wise and sales trend dashboards
6. Engaged with stakeholders to gather feedback and continuously enhance the dashboard functionality and design.



## Power BI Techniques and Knowledge Used:
• Data Modeling involving 5 tables and created dynamic measures for visualization<br>
 ![dynamic measures!](https://github.com/user-attachments/assets/f02d0518-de91-4166-b53f-a96697dd7319)<br><br>
 ![dynamic measures!](https://github.com/user-attachments/assets/835809ad-cfff-4626-b771-c2b499e1b9ec)<br><br>
•	Utilized bookmarks to toggle seamlessly between multiple visuals<br>
 ![Bookmark!](https://github.com/user-attachments/assets/818250b5-890f-4862-a275-2ceb2e225c03)<br><br>
 ![Bookmark!](https://github.com/user-attachments/assets/1517b6ec-2a86-4b6f-9ea0-c15bb21c5edc)<br><br>
•	Developed a tooltip page to display detailed insights, such as top-selling 5 medications for each country and customer age group <br><br>
•	Created TOPN parameter and KPI slicers to filter top/underperforming products <br>
• Used image-based navigation action for page navigation<br>
• Developed dynamic titles that adapt based on the selected slicers and parameters<br>
 ![dymanic title!](https://github.com/user-attachments/assets/ad03ee04-e2a9-4247-bfb7-75873add79a7)<br><br>
• Sales & Customer Analysis domain knowledge


## Dax Functions Used:
Calculate, Switch, Divide, Sum & Sum, Selectedvalue, Variable, Sameperiodlastyear, ALL, Allnoblankrow, If

## Dashboards:
Finance: created P&L statement and its dynamic yearly trend, tracked KPI (net sales, gross margin % and net profit %). benchmarked P&L metrics against last year /target

![finance view!](https://github.com/user-attachments/assets/f1064784-1674-48a4-a9e3-68e41bcca840)


  

Sales: created key metrics (net sales, gross margin(%), and quantity) for customers and products, benchmarked against last year. developed a scatter plot to show customer performance metrics against two benchmarks. built a parameter (tolerance gap) to filter customer groups that lag behind the benchmark 

![Sales view!](https://github.com/user-attachments/assets/b8f53bf5-1d13-4c65-ab0d-c21f12ec2a32)





Marketing: built net sales, gross margin(%), and net profit(%) across regions/markets and products. Examined operation expense and net profit in general

![Marketing view!](https://github.com/user-attachments/assets/19cc0eb3-e864-4cee-b492-55813f995862)



Supply chain: tracked KPI of net error (%), absolute error(%), sales forecast accuracy % and yearly trend. Benchmarked forecast accuracy against last year's performance across customers and products

![Supply chain view!](https://github.com/user-attachments/assets/fcd9f4e4-6b4d-4014-96d3-641c95c191f2)


Executive view: Provided key insights by sub-zone and the company's yearly growth trend in market share against other main players. Analyzed revenue breakdown by product division and sales channel. Highlighted top 5 customers and top 5 products by revenue

![Executive view!](https://github.com/user-attachments/assets/4d16dfaf-1ba2-4a3b-bbdc-ada5e7ec8779)





