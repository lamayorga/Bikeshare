# Bikeshare Data Analysis
## Python Script Exploring US Bikeshare Data
This Python script was written to explore bikeshare data in Chicago, New York City, and Washington by importing data and computing descriptive statistics.

## Datasets
The script includes bikeshare data from [Motivate](https://www.motivateco.com/) for the first six months of 2017. The original data files can be accessed here for [Chicago](https://www.divvybikes.com/system-data), [New York City](https://www.citibikenyc.com/system-data), and [Washington](https://www.capitalbikeshare.com/system-data). Some data wrangling was performed prior to building the script to reduce columns, reformat and filter through relevant data.

All three cities contain information in these six categories:
 * Start Time
 * End Time
 * Trip Duration (in seconds)
 * Start Station
 * End Station
 * User Type (subscriber or customer)

Datasets for Chicago and New York City also contain:
* Gender
* Birth Year

## Software
The program was written using:
* Python 3
* NumPy and Pandas installed using Anaconda

## How to Use
1. Download the bikeshare folder onto computer
2. Open terminal
3. Navigate location of bikeshare folder
4. Type /python bikeshare.py/ into terminal
5. Press enter and follow through the script prompts and questions to display relevant data analysis

## Explored Questions
The script answers the following questions using the bikeshare data:

Popular Months, Days, and Times of Travel
* What is the most popular month for start time?
* What is the most popular day of week for start time?
* What is the most popular time of day for start time?

Popular Stations and Trips
* What is the most popular start and end station?
* What is the most popular trip?


Trip Duration
* What is the total trip duration?
* What is the average trip duration?

User Information
* What are the counts of each user type?
* What are the counts of gender? (only available for Chicago and New York City)
* What are the earliest (i.e. oldest user), most recent (i.e. youngest user), and most popular birth years?


## Questions to Consider for Additional Business Analysis
* How does season impact bikeshare use?
* What is the optimal driving time between stations?
* How does the use of bikes vary by city?
* How many bikes should each station have available?
* Are certain user age groups more likely to use the bikeshare system than others?
* Which users are more likely to buy short-term hour passes (i.e. 3-day or 24 hours)?
* Which users are more likely to pay for yearly subscriptions?
* Which user type is likely to take more trips? Users with short-term hour passes or yearly subscriptions?

## Credits
* [Motivate](https://www.motivateco.com/)
  * [Chicago](https://www.divvybikes.com/system-data)
  * [New York City](https://www.citibikenyc.com/system-data)
  * [Washington](https://www.capitalbikeshare.com/system-data)
* [Pandas Documentation](https://pandas.pydata.org/pandas-docs/stable/)
* [Stack Overflow](https://stackoverflow.com/)
* [The Python Standard Library](https://docs.python.org/3/library/)
* [Udacity](https://www.udacity.com/course/programming-for-data-science-nanodegree--nd104)
