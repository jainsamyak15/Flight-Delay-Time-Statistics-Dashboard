# Flight-Delay-Time-Statistics-Dashboard

# Project Description
The Flight Delay Time Statistics Dashboard is a data visualization application built using Python, Pandas, and Dash. It provides an interactive dashboard to analyze and visualize flight delay statistics based on various factors such as airline carrier, weather conditions, National Airspace System (NAS) delays, security delays, and late aircraft arrivals.

The application reads in a CSV file containing airline data and allows the user to input a specific year. Based on the selected year, the dashboard generates line plots that showcase the average delay times for different airlines across different months of the year, categorized by delay types like carrier delays, weather delays, NAS delays, security delays, and late aircraft delays.

The dashboard aims to provide insights into the performance of airlines and the impact of various factors on flight delays, enabling users to make informed decisions or conduct further analysis.

# Features
+ Interactive user interface built with Dash
+ Data visualization using Plotly Express
+ Line plots for different delay types (carrier, weather, NAS, security, late aircraft)
+ Ability to select a specific year for analysis
+ Responsive layout for optimal viewing on different screen sizes
# Installation
To run the Flight Delay Time Statistics Dashboard locally, follow these steps:

1. Clone the repository or download the source code.
2. Ensure you have Python and the required dependencies installed (Pandas, Dash, Plotly).
3. Navigate to the project directory in your terminal or command prompt.
4. Run the following command to start the Dash application: `python Flight_Delay_Time_Statistics_Dashboard.ipynb`
5. The application will start running on http://localhost:3000/. Open this URL in your web browser to access the dashboard.
# Usage
1. Upon opening the application, you will see the Flight Delay Time Statistics Dashboard.
2. Enter the desired year in the "Input Year" field.
3. The dashboard will automatically update and display line plots for different delay types, showing the average delay times for different airlines across different months of the selected year.
4. Interact with the plots by hovering over the lines to see specific delay values for each airline and month.
