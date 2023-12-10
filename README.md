>**Note**: Please **fork** the current Udacity repository so that you will have a **remote** repository in **your** Github account. Clone the remote repository to your local machine. Later, as a part of the project "Post your Work on Github", you will push your proposed changes to the remote repository in your Github account.

### Date created
10 Dec 2023

### Project Title
Creating a bikeshare data analytics program

### Description
See below. 

### Files used
Include the files used: 
- bikeshare.py
- chicago.csv
- new_york_city.csv
- washington.csv

### Credits
Udacity GPT & Udacity Lessons! 

# Bikeshare analytics

Bikeshare.py is a simple program written in Python to explore data related to bike share systems for three major cities in the United States—Chicago, New York City, and Washington. User will be able to select the bikesharing data filtered by city, month and day of the week. Interesting descriptive statistics will be provided depending on the input combination of the user.

## Installtion & Software Dependencies 

Simply run ipython bikeshare.py to run the program. Make sure your terminal is pointing at this directory. 

## Usage Information

- As the first step: users will be prompted to input which city they would like the program to analyse, among the given cities: Chicago, New York City, and Washington. The program takes into account lower-cases and error-handling. 

- Second step: users then will be prompted to choose a month, or all if they don't want to filter the month and the program will analyse data across all months.

- Third step: users will be asked to choose a day of the week (Monday to Sunday). Alternatively, user can say 'all' to not filter any data according to day of the week.

- Fourth step: after seeing some descriptive statistics, users can see some sample raw data, displayed at 5 rows each request that user have (through 'yes' and 'no' prompts)

- Fifth step: finally, user may re-start the application to input a different combination of data filter.

## Descriptive informations to be displayed

Statistics on the most frequent times of travel:
- The most common month
- The most common day of week
- The most common start hour

Statistics on the most popular stations and trip:
- Most commonly used start station
- Most commonly used end station
- Most frequent combination of start station and end station trip

Statistics on the total and average trip duration:
- Total travel time
- Mean travel time

Statistics on bikeshare users:
- Counts of user types
- Counts of gender
- Earliest, most recent, and most common year of birth

## Limitations

The current program does not have a way to add new data (for example, of a new city). Future enhancements could be made to make this more convenient for users to upload more data files to make further analysis.

