# Make a time clock web app

## Interface
Displays current date and time in upper right corner of screen  
"Enter employee number" input field  
This page is called the Home Screen

## Database
The database will contain 5 employee names of your choosing, each with their own unique employee number. The database will also require the necessary fields for each report option that you use from the list below.

## Details
Enter employee number in input field and press Clock In button  
Validate employee number and return error message if number isn't in the database  
If employee number validates, display a new page that will show the following:  

* Upper left corner of the screen displays current employee name and number
* Upper right corner of the screen displays the current date and time
* Clock In button
* Lunch Out button
* Lunch In button
* Clock Out button
* Reports button
* Return Home button

Buttons that aren't a valid option, based on the employee's current status, should be disabled. For example, once the employee is clocked in, the Clock In and Lunch In buttons should be disabled. After clocking out for lunch, the Clock In, Lunch Out, and Clock Out buttons should be disabled.  
The Reports and Return Home buttons should never be disabled.
If punch validates OK, display "John/Jane Doe has successfully clocked in at *current time*" (Make all punch times have appropriate message). This message will display for 5 seconds, then disappear and return to the Home Screen. 
  

## Reports button
After clicking the Reports button, have options to output a report of:

* Total hours worked this week
* Punch in times
* Punch out times
* Total hours in date range
* Total yearly hours worked
* Regular/OT hours worked

