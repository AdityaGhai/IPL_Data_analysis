# Performance Analysis of Players in IPL 2023

Created a Power BI Dashboard which helps to review and compare performances of all the players in tournament. The dashboard also enables us to select best eleven of the tournament based on their performance based on some selection criteria

## Steps:
- ### Data Collection:
    Scrapped all the data regarding IPL match from www.espncricinfo.com using Beautifull Soup library of Python.
    
- ### Data Transformation:
    Performed initial data cleaning after scrapping such as player name correction, match id linking etc. using Pandas.
    Then, transformed the final data for dashboard using Power Query of Power BI.

- ### Data Modelling:
    Connected all the datasets with based on some defined primary keys sucha s team and match ids. Also, created many measures, calculated columns and parameters for data analysis and dashboarding using DAX.
 
- ### Dashboarding:
    Craeted final dashboard using Power BI visuals.
    ```
    

https://github.com/AdityaGhai/IPL_Data_analysis/assets/83689540/5e6a367e-c5a7-4d9a-865a-8da0a358a3d9

![Screenshot 2023-07-25 213300](https://github.com/AdityaGhai/IPL_Data_analysis/assets/83689540/32f82a5b-4f55-467b-9899-65bfcff798ae)


## Tools used:
- Python -> Beautiful Soup, Pandas
- Power BI -> Power Query, DAX
