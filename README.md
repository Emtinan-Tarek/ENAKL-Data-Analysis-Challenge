The primary focus is on deriving insights into busline performance, including the calculation of average fill rates over different weeks.


Data Preparation:

Temporary table creation (#BuslineLaunchDates) to store busline names and launch dates.
Launch dates derived from the last 5 characters of busline names.


Data Extraction and Calculation:

SQL queries to join data from bookings_data with the temporary table.
Calculation of week numbers and average fill rates using the DATEDIFF function.


Data Visualization:

Attempted data visualization using Seaborn and a heatmap for a visual representation of average weekly fill rates for various buslines.
