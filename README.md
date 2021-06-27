# Explore-US-Bikeshare-Data
Exploring data related to bikeshare systems for three major US cities in the United States, using Python.

## Project Overview
This project explores data related to bikeshare systems for three major US cities in the United States - Chicago, New York City, and Washington. In this project, Python code was used to import the data and answer interesting questions about the datasets by computing descriptive statistics. Python scripts were used to take in raw input from the user to create an interactice expereince in the terminal to present the statistics.

## Data Set
In this project, I used data provided by [Motivate](https://www.motivateco.com/), a bike share system provider for many major cities in the United States, to uncover bike share usage patterns. System usage between three large cities: Chicago, New York City, and Washington, DC were compared.
Three city dataset files  were used to explore the bikeshare data: 
•	chicago.csv
•	new_york_city.csv
•	washington.csv


## Statistics Computed
In this project, I used Python code to compute a variety of descriptive statistics. The following information were calcualated:
- Popular times of travel (i.e., most common month, most common day of week, most common hour of day)
- Popular stations and trip (i.e., most common start station,	most common end station, most common trip from start to end)
- Trip duration (i.e., total travel time,	average travel time)
- User info (i.e., counts of each user type, counts of each gender (only available for NYC and Chicago),	earliest, most recent, most common year of birth (only available for NYC and Chicago))


## Interactive Experience
The bikeshare.py file is set up as a script that takes in raw input to create an interactive experience in the terminal that answers questions about the dataset. The experience is interactive because depending on a user's input, the answers to the questions on the previous page will change! There are four questions that will change the answers:
1.	Would you like to see data for Chicago, New York, or Washington?
2.	Would you like to filter the data by month, day, or not at all?
3.	(If they chose month) Which month - January, February, March, April, May, or June?
4.	(If they chose day) Which day - Monday, Tuesday, Wednesday, Thursday, Friday, Saturday, or Sunday?
The answers to the questions above will determine the city and timeframe on which I did data analysis. After filtering the dataset, users will see the statistical result of the data, and choose to start again or exit. 


# Technologies Used
- Python 3, NumPy, and pandas
- A text editor, like Sublime or Atom
- A terminal application (Terminal on Mac and Linux or Cygwin on Windows).


# Resources

### [Programming for Data Science with Python Nanodegree Program](https://classroom.udacity.com/nanodegrees/nd104/dashboard/overview)

# License

### The contents of this repository are covered under the [MIT License](https:aset/blob/main/LICENSE).
