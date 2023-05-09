# 2021 Feb to 2023 Feb Citibike Analysis in Tableau

This project utilized Tableau to analyze and discover phenomena contained within data from New Jersey City's Citi Bike program. The data is publicly available in the form of large CSV files. 

**Below is my step to Orgizies data and idea create analysis in Tableau**
- Citi bike changed the table layout on 2021 Ferruary, This analysisis start to 2021 Feb to 2023 Feb.
- The data files often contained more thousands of rows, I did ETL and make combine date in Pandas, file is call "2021FebTo2023Feb_citibike.csv". 
You can download from here [2021FebTo2023Feb_citibike.csv](https://drive.google.com/file/d/1HcYfcdiafiV2iHEYtsLG8MlpYSCN21N1/view?usp=share_link)
- There were many stations with incorrect latitudes and longitudes or station identifiers.
- There were many stations that had more than one identifier associated with it.
- Some bikes were rented and then later returned, but there was no information on where they were returned.
- The amount of data for a full year's analysis was too large for Tableau Public to handle.
