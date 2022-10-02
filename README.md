### Adventure Works Report
consists of visuals, that represent different findings 
and insights from the dataset. 

It is based on data from CSV tables: `AW_Calendar_ Lookup`, 
`AW_Customer_Lookup`, `AW_Product_Categories_Lookup`, `AW_Product_Lookup`, 
`AW_Product_Subcategories_Lookup`, `AW_Returns`, `AW_Sales_2015-2017`, `AW_Territiries_Lookup`.
There were also added a range of calculated columns and measures, created with DAX functions.

The tables are related to one another (relation one-to-many `1:*`). Please check
the relationship model screenshot below:

![This is an image](https://github.com/KaterIva/Adventure_Report_PBI/blob/master/AW_data_model.PNG?raw=true)

The report consists of three tabs: 
- `Exec Summary` - eleven different visuals and 
two bookmarks, you can filter content by date using the slicer on the top and drill through treemap 
`Total Orders by Category`, explore product subcategories, return rate, monthly revenue, monthly orders 
and returns
- `Product Details` - nine different visuals, here you can see current 
month orders, Revenue and Returns vs. Target by every product, Weekly Profit Forecast based on price 
adjustment and weekly return volume)
- `Customer Details` - nine different
visuals representing total orders by customer name, gender, income level, occupation, current age etc.  

The filters are applied to all report pages, you can interact with content.

<sub>(click to start demo)</sub>
![This is an image](https://github.com/KaterIva/Adventure_Report_PBI/blob/master/adventureWorksDemo.gif?raw=true)

<sup>*Based on the course “Microsoft Power BI Desktop for Business Intelligence” by Maven Analytics, Chris Dutton*</sup>