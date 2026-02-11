# Excel EDA of King Fahad National Library 2024
**Exploratory Data Analysis (EDA) and an interactive dashboard analyzing the beneficiaries 
of King Fahad National Library for the year 2024 using Excel**


##  Features
- Cleaned and translated to English data.
- Interactive and visually appealing dashboard.  
- Clear and easy-to-read data visualizations highlighting trends.  
- Pivot tables for detailed and flexible data exploration.  
- Dynamic slicers by month, quarter, and service type.  
- Insights into visitor trends and beneficiary satisfaction.

##  Insights 
- Sundays have the highest number of visitors each week.
- Certain services like e-research support are more popular than others
- Monthly trends show peak total visitors during event-heavy quarters
- The dashboard helps identify underutilized service hours.

## Dashboard  
 1- The following screenshot displays the dashboard with no filters or slicers applied. 
 <img width="2510" height="1321" alt="لقطة شاشة 2026-02-11 034534" src="https://github.com/user-attachments/assets/70b65136-3f5a-4a5b-9c7c-139a2027e3af" />

 2- The second screenshot display the dashboard after specific slicers have been applied
<img width="2803" height="1481" alt="لقطة شاشة 2026-02-11 033934" src="https://github.com/user-attachments/assets/253539fd-d5ba-4ec7-98c0-6860b4bc1b4a" />

## Pivot Tables 
The dashboard is linked to Pivot tables allowing for easy navigation between the summary and the detailed data
<img width="1489" height="750" alt="لقطة شاشة 2026-02-11 034113" src="https://github.com/user-attachments/assets/d93f0aee-ab23-4705-98dd-b1fdcd0dfb32" />
<img width="1792" height="724" alt="لقطة شاشة 2026-02-11 034324" src="https://github.com/user-attachments/assets/3677c3f1-65d9-44c6-b7db-c1f275d712bc" />

 ## Excel Forumlas  
Spliting Days from Date coulmn 
```
=TEXTSPLIT(DateCell, " ") 
```
Exracting quarters from date:
```
="Q"&ROUNDUP(MONTH(DateCell)/3;0)
```
 Exracting months from date:
```
=TEXT(DateCell;"mmm")
```
Counct of Total events days:
```
=EndDateCell - StartDateCell +1
```

## Dataset source 
  - [Open Data Platform](https://open.data.gov.sa/en/home) - Official Saudi government website
  - [King Fahad National Library](https://kfnl.gov.sa/En/Pages/default.aspx) - Library's official website




