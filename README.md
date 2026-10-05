# Temporal and Vertical Patterns in Microbial ATP at Station ALOHA
## Predict ATP values in stations that do not include ATP but have other variables such as chlorphyll and carbon

This project examines how microbial ATP concnetrations vary vertically and temporally at Station ALOHA using the Hawaii Ocean Time series (HOT) data collection program. CTD pressure is used as a vertical measurement for depth, assuming 1 decibar is approximately 1 meter in depth. Since HOT is the only place to get public ATP data, I would like to apply a regression to the relationship between ATP and other variables to predict what the ATP values may be in areas lacking ATP collection data. 

### Data source

Data were accessed through HOT-webODV
Mieruch, S. & Schlitzer, R., HOT-webODV, https://hot.webodv.awi.de , 2026.
https://hot.webodv.awi.de/data

### Project files

The exploratory data analysis is located in: /CODE/hot_atp_exploratory_data_analysis.ipynb