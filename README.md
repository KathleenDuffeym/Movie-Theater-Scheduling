# Movie Theater Scheduling
A repository for group 16 for the ISE project on Movie Theater Scheduling

### Project Members
Kathleen Duffey, Joshua Higgins, Tina Wang

### Submission Date
11/25/2024

## How to Use
This project creates an objective function that can be used to maximize the theater production schedule for a given theater on a given day. 
The output of the function is the optimal scheduling windows, with times and movie names, given a popularity index for movies and time slots,
 as well as theater capacity and movie length.  Additionally, the function returns the expected optimal income from that day, as well as the 
 tickets, showings, and income from each time slot and movie.

In order to use this code for alternative theaters, simply adjust the constants and slots to fit any movie theater's constraints.  Alter the 
loop invariants to change the number of timeslots in a day, or the number of movies. 

To calculate our movie popularity, we used a mixture of IMDB popularity results as well as awards and accolades, then combined this into an 
index vector. 

For timeslot popularity, we utilized the google analtyics to adjust based on the busiest times for the theater.

Finally, any other theater statistics came directly from the website, and any other movie statistics from the IMDB page.

## How to Run

First, open a new file in Jupyter notebook using Anaconda or another alternative software.  Load the "ISE3230 Final Project" file into the notebook,
and compile the code.
