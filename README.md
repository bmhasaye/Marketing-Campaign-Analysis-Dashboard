**MARKETING CAMPAIGN ANALYSIS USING POWER BI DESKTOP**

This project uses Microsoft Power BI Desktop to Transform, load and visualize the data.<br/>
<br/>
<br/>

**DAX FORMULAS USED**

Total Purchase = SUM(ifood_df[No.CatalogPurchases]) + SUM(ifood_df[No.DealsPurchases]) + SUM(ifood_df[No.StorePurchases]) + SUM(ifood_df[No.WebPurchases])

Target Response = 0.15* SUM(ifood_df[Response])

Campaign Profit = SUM(ifood_df[Z_Revenue]) - SUM(ifood_df[Z_CostContact])

% Success = (SUM(ifood_df[Response])) / (SUM(ifood_df[Campaign_Overall]))

<br/>
<br/>

**DATASET**
The dataset used is uploaded and the source is Kaggle.<br/>
<br/>
<br/>
**DASHBOARD**
![image](https://drive.google.com/file/d/1ybLlJvsIYktsoWoUMNQzXNtC7yX8yJN7/view?usp=sharing)<br/>
<br/>

![image](https://github.com/bmhasaye/Marketing-Campaign-Analysis-Dashboard)
