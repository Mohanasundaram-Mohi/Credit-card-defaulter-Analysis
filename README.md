# Credit card defaulter Analysis - Dashboard

I've just finished analysing the Credit card defaulter Analysis. My dynamic Power BI dashboards delve deep into factors that help to understand defaulters status, repayments etc.. 

 ## Here's what you can expect from this dashboard:

🛠️ Toolkit: Power BI, Microsoft Excel

📊 Datasets: Microsoft Excel

Project Overview:

1. Defaulters with different shades like with education, martial, gender. 
2. Cards to show defaulters, customers, sum of bills and repaid 
3. Defaulters with age groups and credit limit defaulters 
4. Re-payment status of each month. 

DAX : 
Defaulters = CALCULATE(Count(Data[default payment next month]),Data[default payment next month]=1)

Sum of Bills = SUMX(Data,Data[Total Bill]*1)

#
Dashboard Screenshot

![Screenshot (24)](https://github.com/Mohanasundaram-Mohi/Credit-card-defaulter-Analysis/assets/168515064/aeed115e-6334-4d63-844f-97e1e1e2085d)



 
