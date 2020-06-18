# Bikeshare
## Python Script Exploring US Bikeshare Data
This Python script was written to explore bikeshare data in Chicago, New York City, and Washington. This script imports data and computes descriptive statistics.

###### Data Sets
The script includes data sets of bikeshare data for the first six months of 2017. The original data files can be accessed here for [Chicago](https://www.divvybikes.com/system-data), [New York City](https://www.citibikenyc.com/system-data), and [Washington](https://www.capitalbikeshare.com/system-data). Some data wrangling was performed prior to building the script to reduce columns, reformat, and filter relevant data.

[Motivate](https://www.motivateco.com/), the bike share system provider for many cities in the US, provided the data for these cities. All three cities contain the following six columns:

 * Start Time
 * End Time
 * Trip Duration (in seconds)
 * Start Station
 * End Station
 * User Type (Subscriber or Customer)

While Chicago and New York City files also contain two additional columns:

* Gender
* Birth Year

###### Software
The program was written using:
* Python 3
* NumPy and Pandas installed using Anaconda

###### Run the script
The script is written in Python and uses csv, datetime, pandas, and time. These packages are necessary to launch the script. Upon launching the bikeshare.py file from the terminal, a prompt will guide the user through the bikeshare data and display relevant data analysis.

How to run the script:
1. Download the bikeshare folder onto computer
2. Open terminal
3. Navigate location of bikeshare folder
4. Type "/python bikeshare.py/" into terminal
5. Press enter and follow through script prompts and questions to unveil relevant data

###### Explored Questions
The script answers the following questions about the bikeshare data:

Popular Months, Days, and Times of Travel
* What is the most popular month for start time?
* What is the most popular day of week for start time?
* What is the most popular time of day for start time?

Popular Stations and Trip
* What is the most popular start and end station?
* What is the most popular trip?


Trip Duration
* What is the total trip duration?
* What is the average trip duration?

User Information
* What are the counts of each user type?
* What are the counts of gender? (only available for Chicago and New York City)
* What are the earliest (i.e. oldest user), most recent (i.e. youngest user), and most popular birth years?


###### Additional Questions to Consider for Business Analysis
* How does season impact bikeshare use?
* What is the optimal driving time between stations?
* How does the use of bikes vary by city?
* How many bikes should each station have available?
* Are certain user age groups more likely to use the bikeshare system than others?
* Which users are more likely to buy short-term hour passes (i.e. 3-day or 24 hours)?
* Which users are more likely to pay for yearly subscriptions?
* Which user type is likely to take more trips? Users with short-term hour passes or yearly subscriptions?

###### Resources
* [Pandas Documentation](https://pandas.pydata.org/pandas-docs/stable/)
* [Stack Overflow](https://stackoverflow.com/)
* [The Python Standard Library](https://docs.python.org/3/library/)
