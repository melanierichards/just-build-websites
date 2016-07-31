# Make a time clock app

## Interface
Displays current date and time in upper corner of screen<br>
"Enter employee number" input field<br>
Buttons:

* Clock In
* Lunch Out
* Lunch In
* Clock Out
* Reports

The database will contain 5-10 employee names (of your choosing), each with their own unique employee number. Database will also require a field for whatever report options that you use from the list below

## Details
Enter employee number in input field and press Clock In button<br>
Validate employee number and return error if number isn't in the database<br>
Validate clock in status (make sure not already clocked in) and return error if already clocked in "Error: John Doe has already clocked in"<br>
If punch validates OK, display "John Doe has successfully clocked in at *current time*" (Make all punch times have appropriate message)<br>
Validate all time clock punches like any time clock should work, i.e. return error if they try to clock out when the last thing they did was clock out for lunch, don't let them punch out if they forgot to punch in, etc.

## Reports button
After clicking Reports button, have options to output a report of:

* Total hours worked this week
* Punch in times
* Punch out times
* Total hours in date range
* Total yearly hours worked
* Regular/OT hours worked

