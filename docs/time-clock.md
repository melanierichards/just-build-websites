# Make a time clock web app

## Interface
Displays current date and time in upper corner of screen  
"Enter employee number" input field  
Buttons:

* Clock In
* Lunch Out
* Lunch In
* Clock Out
* Reports

The database will contain 5 employee names of your choosing, each with their own unique employee number. The database will also require the necessary fields for each report option that you use from the list below

## Details
Enter employee number in input field and press Clock In button  
Validate employee number and return error if number isn't in the database  
Validate clock in status (make sure user is not already clocked in) and return error if already clocked in "Error: John/Jane Doe has already clocked in"  
If punch validates OK, display "John/Jane Doe has successfully clocked in at *current time*" (Make all punch times have appropriate message)  
Validate all time clock punches like any time clock should work, i.e. return error if they try to clock out when the last thing they did was clock out for lunch, don't let them punch out if they forgot to punch in, etc.  

## Reports button
After clicking the Reports button, have options to output a report of:

* Total hours worked this week
* Punch in times
* Punch out times
* Total hours in date range
* Total yearly hours worked
* Regular/OT hours worked

