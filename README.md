

# HighCloud Airlines-Dashboard

## Problem Statement

This dashboard helps the airlines understand their customers better. It helps the airlines know if their customers are satisfied with their services. Through the Load Factor, they get to know their improvement area, & thus they can improve their services by identifying these area.  thus since by using this dashboard they have identified this problem, they can further work on those factors.

Since, number of neutral/dissatisfied customers (almost 45 %) are more than satisfied customers (around 55 %), thus in all they should have to work more on improving their services for more customers satisfaction. 


### Steps followed 

 Step 1: Data Preparation in Excel:

Dataset loaded as a CSV file into Excel.
Opened Power Query Editor to process and transform the data.

Step 2: Data Profiling:

Enabled “Column Distribution,” “Column Quality,” and “Column Profile” under the View tab in the Power Query Editor.
Changed the column profiling to analyze the entire dataset instead of just the first 1000 rows.

Step 3: Data Cleaning:

Observed that most columns were error-free, except for
Available Seats: Null values replaced with 0 to ensure accurate Load Factor calculation.

Destination State and Origin State: Null values replaced with “N/A.”

Step 4: Data Transformation:

Created conditional columns:
Distance Group: Based on Distance Group ID.

Day Type: Categorized flights into weekdays or weekends.
Financial Quarter and Month: Derived from date fields.
Added a custom column to calculate the Load Factor using the formula:

Load Factor = (Transported Passengers / Available Seats) * 100

Visualization Filters (Slicers):

Added slicers for fields like Class, Region, Year,Financial Quarter, Financial Month and Day Type to enhance interactivity.

  # Load Factor Analysis Dashboard         
Step 5 : 
- Line Chart: Represents the load factor percentage on a yearly, quarterly, and monthly basis.

- Bar Chart  : Highlights the load factor percentage for each carrier, with Delta Airlines achieving the highest load factor of 20%.

- Year-over-Year (YoY) Change Bar Chart: Displays percentage changes in the load factor for comparative annual performance.

- Donut Chart: Compares load factor utilization between weekends and weekdays.

- Some Cards Like Total Seats, Total Passengers, Average Load factor, Total Distance.

Snap of Load Factor Analysis Dashboard,

![LoadFactor](https://github.com/user-attachments/assets/08868257-6c54-4839-ae1c-ebb88fa56b7d)

# Insights

- Overall Load Factor:

      The average load factor for the airline is 55%, which means that 55% of the seats available are occupied by passengers.
      This is a relatively high load factor, indicating that the airline is utilizing its aircraft efficiently.

- Load Factor by Year, Quarter, and Month:

      The load factor fluctuates throughout the year, with higher values in certain Year.
      The highest load factor is in 2011 at 17.42%.

- Load Factor by Carrier:

      The dashboard shows the top carriers based on load factor,
      Delta Air Lines Inc. has the highest load factor at 20%,
      Southwest Airlines Co. and US Airways Inc. follow closely with load factors of 19% and 11%, respectively.

- Load Factor by Day Type:

      Weekdays have a higher load factor (71.17%) compared to weekends (28.83%).

- Year-over-Year (YOY) Change in Load Factor:

      The YOY change in load factor shows a fluctuating trend, with both positive and negative changes.
      The highest positive change is 7.42% in 2010.
      The largest negative change is -3.15% in 2012.

# Potential Areas for Improvement:

Increase load factor during off-peak seasons: The airline can focus on strategies to increase demand during periods with lower load factors. This could involve offering promotional fares, targeted marketing campaigns, or partnerships with travel agencies.

Optimize flight schedules: By analyzing passenger demand patterns, the airline can adjust flight schedules to align with peak travel times, potentially increasing load factors.

Improve customer experience: Providing excellent customer service can lead to repeat business and higher load factors. The airline can focus on areas such as on-time performance, baggage handling, and customer support.

# Flight Operations Dashboard
Step 6: 
- Bar chart: Top 10 Carrier name by Passengers Preferences.

- Bar chart: Top Routes Based on No. of Flights.

- Bar chart: No. of Flights on Distance Groups.

- Bar chart: Flights by Region.

Snap of Flight Operations Dashboard,

![FS_Dashboard](https://github.com/user-attachments/assets/29724a52-33ca-40ac-ae32-af98f0c94198)

# Insights

- Overall Operations:

      The airline operates a total of 207 airlines with 106 routes,
      It has a total seat capacity of 244 million and covers a   total distance of 82 million.

- Top Carriers by Passenger Preference:

      Delta Air Lines is the most preferred carrier, followed by Southwest Airlines and Federal Express.

- Top Routes Based on Number of Flights:

      The route with the highest number of flights is Chicago, IL - Detroit, MI with 95 flights.
      Other top routes include Washington, DC - New York, NY, Charlotte, NC - Atlanta, GA, and Chicago, IL - Atlanta, GA.

- Number of Flights by Distance Group:

      The majority of flights are short distance, followed by medium distance.
      There are a relatively small number of long-distance and very long-distance flights.

- Flights by Region:

      The airline operates primarily in the domestic region, followed by Latin America.
      International, Pacific, and Atlantic flights account for a smaller portion of the total.

# Potential Areas for Improvement:

Expand long-Distance routes: The airline could consider expanding its long-Distance routes to tap into new markets and increase revenue.

Optimize route network: Analyzing passenger demand and route profitability can help optimize the route network to improve efficiency and reduce costs.

Increase international presence: The airline could explore opportunities to expand its international operations to capture a larger share of the global market.  

# Search Flights Tool

Focus:

A tool created to allow users to search for specific flights based on filters like Source and Destination.
        
Snap of Search Flights ,

![SFTool](https://github.com/user-attachments/assets/eb985b58-946c-4a96-a8bf-53f4bd3c710d)

