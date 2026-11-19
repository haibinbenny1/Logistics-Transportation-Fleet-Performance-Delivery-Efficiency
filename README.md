# Logistics & Transportation – Fleet Performance & Delivery Efficiency

## Project Overview

This project analyzes fleet performance and delivery efficiency using Microsoft Power BI.

The main objective is to understand delivery performance, fuel efficiency, distance travelled, and transportation costs.

## Dataset

The project uses two datasets:

**1. Trip_Data**
- Trip ID
- Vehicle ID
- Driver ID
- Origin
- Destination
- Distance (km)
- Fuel Consumed (L)
- Delivery Status
- Delivery Date

**2. Vehicle_Master**
- Vehicle ID
- Vehicle Type
- Capacity (kg)
- Maintenance Cost

## Data Cleaning & Modelling

- Removed unnecessary columns.
- Created a unique Trip ID.
- Corrected column data types.
- Identified and replaced an invalid distance value using the median.
- Checked missing values.
- Created a One-to-Many relationship between Trip_Data and Vehicle_Master using Vehicle_ID.
- No missing fuel consumption values were found.

## DAX Measures

The following measures were created:

- Total Trips
- On-Time Trips
- On-Time Delivery Percentage
- Total Distance
- Total Fuel Consumed
- Fuel Efficiency
- Total Fuel Cost
- Total Maintenance Cost
- Cost Per Km

**Fuel price assumption:** ₹95 per litre, as specified by the mentor.

## Dashboard Pages

### Page 1 – Executive Overview

Includes five Card visuals displaying:

- Total Trips – 50
- On-Time Delivery – 60%
- Fuel Efficiency – 11.68 km/L
- Total Distance
- Cost Per Km – ₹9.54

**Charts:**
- On-Time Delivery Percentage by Route – Bar Chart
- Monthly Fuel Efficiency Trend – Line Chart

### Page 2 – Delivery Performance Map

- Displays delivery performance by origin city.
- Uses map bubbles to represent trip counts.
- Shows Late and On-Time delivery status through the legend.
  
## Conclusion

This project demonstrates how Power BI can be used to analyze logistics and fleet performance.

The dashboard provides insights into delivery performance, fuel efficiency, distance travelled, and transportation costs, helping understand fleet operations and identify areas for improvement.

