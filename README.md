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

Using the tools listed above, I was able to create a table in python in which I could clean up and locate missing values, along with the areas to which they belong to. With simple refinement, I was then able to create a basic pie chart that visualized **The Top 10 Electric Vehicle Makes in the State of Washington.** For further visualization, using the same refined data set, I then prompted to create a barplot that displayed **The Top 10 Cities in Washington with the Most Amount of Electric Vehicles.** As added experience and challenge, I even went the extra mile to include the demonstration of folium, setting a visualize map that showed the concentrations of EV's in Washington using the longitude and latitude of each registered vehicle. With this information in hand, I decided to further analyze **Teslas in Seattle**, *the most popular EV Make in the city of the most amount of EV's in Washington*. In doing so, I was challenged to create my own data frame using information I'd gather online, most notably each make's kWh consumption through Tesla's website. Calculating both their average consumption and electric range, I was then able to determine the total consumption and cost of traveling this range. To provide an even deeper analysis, I created another data frame pertaining to *The Top 5 Gas Cars in Seattle* to compare with. In the end, I was able to gather the `Miles Per Gallon` of each car, `Total Gallons to Travel the Equivalent of Tesla's Average Electric Range`, and finally each car's `Fuel Cost`. Combining these two data frames in an alternating arrangement, I then translated it into a barplot that compared **The Top 5 Gas Cars** with **Tesla's 4 Models and 1 Combined Average.** My findings: a significant difference in cost between driving a traditional gas car vs. driving one of Tesla's models.

# ⚠️ Improvements 

During the process of this analysis, many assumptions were made in order to simplify the data. For example, gas prices were a calculated average from the BLS, the data of the top 5 popular cars being based on 2025 models, and an average of each Tesla model's consumption rather than a specific variation. Because of this, the data shown is more generalized rather than taking a specific case into consideration. As for rooms for improvement, perhaps one could include up-front costs of electric vehicles vs traditional gas cars, The total maintenance cost to own either electric or gas, and maybe even a comparative analysis on the different EV makes in different cities.
