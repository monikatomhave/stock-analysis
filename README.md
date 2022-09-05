Stock Analysis data

The purpose of this project is to take a database of stock data from two years for 12 different stocks and give us the total daily volume of the stock and the yearly return for each of those stocks was up or down.  Also the chaellege was to refactor the code written during the module and refactor it to get it to run faster. 

Results:
    After the code looped through and had a total volume stored for each stock, it calculated the annual percentage return.  The origial code from the module ran at 1.99 seconds and 1.38 seconds for the years 2017 and 2018, respectively.  The images 2017 and 2018 attached to this repository show the runtimes for each year.  Once the code was refactored to only loop through once, the run times for each year of 2017 and 2018 were .1875 seconds and .171875 seconds, respecitvely.  These images of the times can be found in the images 2017refactored and 2018refactored that are attached in this repository.

Summary:
    Clearly the code ran much faster once refactored.  This isn't much of a difference with this size of a database, but if the database were much larger, the code would have taken much longer to run. Saving time and energy.  Of course doing each one individually you could print out each one as you go and keep data seperated.  The code once refactored is a lot less and easier to read and edit.  