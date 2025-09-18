# Electric-Vehicles-in-Washington-Data-Analysis

An Exploratory and Comparative Analysis on Electric Vehicles in Washington State.

# 🚀 Purpose

The purpose of this project was to experiment in representing large amounts of Data using basic Python fundamentals.  
Developing Skills in the following: Data Representation, Data Visualization, Comparative Analysis, Data Insight, Data Interpretation, Data Gathering.

# 📁 Files & 🔗 Links

- Electric Vehicle Population Data: *https://data.wa.gov/api/views/f6w7-q2d2/rows.csv?accessType=DOWNLOAD* # Data Set Used
- Seattle's Utility Rate: *https://www.seattle.gov/city-light/residential-services/billing-information/rates#periods*
- Tesla Model's kWh Consumption: *https://www.tesla.com/en_qa/support/power-consumption*
- Average Fully Charged Tesla kWh: *https://electriccartalks.com/how-many-kwh-to-charge-a-tesla/*
- Top 5 Cars in Washington: *https://stacker.com/stories/washington/most-popular-used-cars-washington*
- Fuel Economy: https://www.fueleconomy.gov/
- Average Gas Prices in Seattle: *https://www.bls.gov/regions/west/news-release/2025/averageenergyprices_seattle_20250121.htm*




# 🔍 Project Goals

- Cleaning Large Data Sets w/ Missing or Incomplete Values
- Data Visualization Using Pie Chart
- Data Visualization Using Barplot
- Data Visualization Using Folium Maps

# 🛠️ Tools Used

- Python 3
- Jupyter Notebook
- Pandas
- Matplotlib / Seaborn
- Folium

# 📈 Key Findings

- Most Popular EV by more than 50% is Tesla
- Most Popular City with EV is Seattle
- Geological Concentration of EV in Washington
- Cost of Charging EV vs. Cost of Fueling Traditional Car

# Summary

Using pandas to create a table in python, I was able to clean the data and locate missing values, along with the areas to which they belonged. Using Matplotlib / Seaborn, I created a pie chart that represented the top 10 electric vehicle makes in the state of Washington. Furthermore, I also created a barplot that displayed the top 10 cities with the most electric vehicles. With the use of folium, I was even able to visualize a map that showed the concentrations of EV's in Washington using the longitude and latitude of each registered vehicle. With this information in hand, I decided to further analyze Teslas in Seattle, the most popular EV in Washington in the top city with the most EV's. As a result, I created a completely new data frame using gathered information pertaining to their kWh consumption through Tesla's website. Calculating their average electric range from the data file, I was then able to determine the total consumption and cost of traveling this electric range. To provide an even deeper analysis, I created another DataFrame on the Top 5 Gas Cars in Seattle to compare with. In the end, I was able to gather the mpg of each car, how many gallons it took to travel the average electric range, and finally each car's fuel cost. Combining these two data frames, I then translated them into a barplot that compared the Top 5 Gas Cars with Tesla's 4 Models and 1 Combined Average. The conclusion, a significant difference in cost between driving a traditional gas car vs. driving one of Tesla's Models.

# ⚠️ Improvements 

During the process of this analysis, many assumptions were made in order to simplify the data. For example, the gas prices were a calculated average from the BLS, the data from the top 5 popular cars were based on 2025 models, and Tesla year models were not factored. As for steps for improvement, one could include up-front costs of electric vehicles vs traditional gas cars, maintenance cost in all vehicles, and a comparative analysis on the different EV makes and/or different cities and seeing how they compare with each other.
