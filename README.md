# Customer-Personality-Analysis

## Data Cleaning and Preprocessing (Performed using Excel Power Query)

* Imported the **Customer Personality Analysis** dataset into **Excel Power Query** using **Data → Get Data → From Text/CSV** for efficient data transformation and preprocessing.
* Removed rows containing missing values (`null`) from the **Income** column to ensure data quality.
* Identified and removed duplicate records to maintain dataset consistency and eliminate redundant entries.
* Changed appropriate column data types, including converting the `Dt_Customer` column to **Date** format for accurate analysis.
* Removed unnecessary columns such as `Z_CostContact` and `Z_Revenue` to reduce redundancy and improve dataset usability.
* Detected and analyzed outliers in the **Income** column to identify abnormal values.
* Created a new **Income Status** column using conditional logic to segment customers into:
     * **High Income**: Above 90,000
     * **Middle Income**: 50,000 to 90,000
     * **Low Income**: Below 50,000
* Created a **Total Spending** column by aggregating customer spending across all product categories.
* Created a **Total Children** column by combining `Kidhome` and `Teenhome` values.
* Created a **Total Campaign Accepted** column to calculate the total number of marketing campaigns accepted by each customer.
* Prepared the cleaned and transformed dataset for further analysis and dashboard development in Excel and Power BI.
