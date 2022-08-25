# Retail Data Analysis
### Architecture:
![image](https://user-images.githubusercontent.com/60545540/186588369-47f9a6ec-5409-45c6-9fec-77cddaf02d53.png)

### Tasks performed:
1. Reading the sales data from the Kafka server
2. Preprocessing the data to calculate additional derived columns such as total_cost etc
3. Calculating the time-based KPIs and time and country-based KPIs
4. Storing the KPIs (both time-based and time- and country-based) for a 10-minute interval into separate JSON files for further analysis
