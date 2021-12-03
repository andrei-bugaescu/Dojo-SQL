# Dojo-SQL


Question 1: How can you retrieve all the information from the facilities table?
Expected result should have 9 rows

Question 2: You want to print out a list of all of the facilities and their cost to members. How would you retrieve a list of only facility names and costs?
Expected result should have 9 rows


Question 3: How can you produce a list of facilities that charge a fee to members?
Expected results should have just 5 rows:


Question 4:  How can you produce a list of facilities that charge a fee to members, and that fee is less than 1/50th of the monthly maintenance cost? Return the facid, facility name, member cost, and monthly maintenance of the facilities in question.
Result is just two rows


Question 5: How can you produce a list of all facilities with the word 'Tennis' in their name?
Expected result is 3 rows


Question 6: How can you retrieve the details of facilities with ID 1 and 5? Try to do it without using the OR operator.
Expected result is 2 rows


Question 7: How can you produce a list of members who joined after the start of September 2012? Return the memid, surname, firstname, and joindate of the members in question.
Expected result is 10 rows
 

Question 8: How can you produce an ordered list of the first 10 surnames in the members table? The list must not contain duplicates.
Expected result should be 10 rows if you include GUEST as a last name
 

Question 9:  You'd like to get the signup date of your last member. How can you retrieve this information?
Expected result should be 1 row (1 date)



Question 10: Produce a count of the number of facilities that have a cost to guests of 10 or more.
Expected result should be 1 row (resulting from a calculation)
 
---------------------------------------------------------------------------------------------------------------------------------------------------------------
Optional

Question 11:  Produce a list of the total number of slots booked per facility in the month of September 2012. Produce an output table consisting of facility id and slots, sorted by the number of slots.
Expected result is 9 rows
	


Question 12:  Produce a list of facilities with more than 1000 slots booked. Produce an output table consisting of facility id and total slots, sorted by facility id.
Expected result is 5 rows


Question 13: How can you produce a list of the start times for bookings for tennis courts, for the date '2012-09-21'? Return a list of start time and facility name pairings, ordered by the time.
Expected result is 12 rows


Question 14:  How can you produce a list of the start times for bookings by members named 'Henrietta Rumney'?
Expected result is 210 rows of timestamps
