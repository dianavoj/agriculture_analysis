# Karnataka Crop & Climate Analysis
AWS + SQL Snowflake + Power BI project analysing crop data

**Background** <br/>
Examining how rainfall, temperature, humidity relate to crop-yield in Karnataka. 

**Business problem/(goal)** <br/>
Establishing how climate conditions and location, season, crop relate to crop yields across Karnataka to target the right crops to the right regions and seasons.

**Objectives** <br/>
- Quantify how average rainfall, humidity and temperature vary by year, season, crop and location
- Identify which crops and locations achieve the highest and lowest average yields
- Compare performance across three growing seasons
  
**Data Description** <br/>
- 3158 records
- csv record
  
**Assumptions/limitations for the data**<br/>
- Initial dataset contains unreliable temperature with soem records reaching 222 degrees
- Missing data in the soily type
  
**Methodology** <br/>
- Data stored in AWS S3
- Snowflake
- Data cleaning, identifying missing values and out of range temperature values
- Aggregation of averages for rainfall, humidity, temperature and yield along four dimensions - year, season, crop, location
- Power BI dashboard for visualization
  
**Key Findings**<br/>
- Coconut is the highest yielding crop with the largest number of records
- Cotton is the highest yielding crop overall
- Rainfall is consistent accross years, locations, crops and seasons
- Humidity is consistent across years, locations, crops and seasons
- Temperature records are unreliable overall
- Some areas (Kodagu) produce higher average yields compared to other areas (Davengere)
- 
**Data Visualization**<br/>
1.
<img width="1102" height="618" alt="image" src="https://github.com/user-attachments/assets/44d359b0-fd8a-4ee3-a256-562c37152c0e" />
2.
<img width="1102" height="622" alt="image" src="https://github.com/user-attachments/assets/40955e47-8291-457f-8a6a-7772ce94da3a" />
3.
<img width="1106" height="620" alt="image" src="https://github.com/user-attachments/assets/7850ff4a-f804-4215-92e0-25b833cde562" />
4.
<img width="1103" height="619" alt="image" src="https://github.com/user-attachments/assets/a313d03e-39e8-4fe3-829e-fdeaf01cf69a" />


**Potential business impact** <br/>
- Matching well-sampled and high-yield crops to their strongest districts and seasons to ensure high yield growth
- Further analysis to establish the price of crop per unit would be beneficial



