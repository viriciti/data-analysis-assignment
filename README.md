# ViriCiti Data Analysis Assignment
![
](https://imgs.xkcd.com/comics/convincing.png)

## Goal
Determine the time spend in the four different energetic states of a vehicle during a day and calculate the efficiency (km/soc%).

## Getting Started
First of all, fork the repository at:

`https://github.com/viriciti/data-analysis-assignment`

Then open up your terminal and clone the forked repository

<sup>Replace [YOUR_USERNAME] with your name</sup>

`git clone https://github.com/[YOUR_USERNAME]/data-analysis-assignment.git`

Enter the directory

`cd data-analysis-assignment`

## The Assignment

### The Data
In the directory `data` you will find a comma seperated file containing all data you need for this
assignment. The data originates from an electric bus recorded during one day. It contains the following columns:
- `datetime`
- `timestamp [ms]`
- `current [A]`
- `voltage [V]`
- `soc [%]`
- `distance [km]`
- `speed [km/h]`

### The Task
Your task is to determine how long the vehicle spends in one of the four energetic states. 
These states are *consuming energy*, *recovering energy*, *idling* and *charging*.
Calculate for each state how much energy (kWh) is involved.

Finally, compute the battery efficiency, which is defined as (consumed energy) / (percentage soc).

Show us how you came to the different states and the efficiency and support it by relevant plots.
You may use the tools of your choice (although we like python ;))

## Questions
If you have an questions about the assignment of project setup, feel free to contact us in the usual
way.

Good luck with the assignment.
