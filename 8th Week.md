I messaged the professor about getting the database to input for the PostgreSQL program. I saw that it required a change of date format. When I ran that command, it did not work.

Changin the format of the date, or datestyle, has become more difficult than I expected. I was using the set command, which I thought would work, but then I read somewhere that the set command is only temporary. I've been checking if the date has changed based on using "select current_date;". 

I decided to start inputing the tables and data into the database not all at once, but in groups and tackle things from there. Creating the tables was not a problem, as I was able to copy and paste the table in and it was created. Doing so with the values into the tables was another thing. It inputed the values, but once I tried to see all of it, it started messing things up. I would use "select * from rep;" and it would bring up the values from the table, but then it would have a bunch of ~ under it, then the word "END", but I could not do anything after that. It seemed to make my terminal freeze, or something along those lines. The current plan is to manually input the values instead of copying it and see how that works. That plan, however, will take a lot of time. 

To remove the table and values, I just used "drop table rep;" and "drop table customer;". I created the tables the same way, but decided to type out the values instead of copy and paste. Doing so resulted in the same problem. So I'm going to type everything out for a table to make sure I do not run into whatever problem this is. 

Typed everything out instead of copy and paste and it still gave me the same problem. I started looking at the examples in the article and it had the column names listed for each value inserted, so I might try that route.

I tried typing everything out a different way, but ran into another problem I'll have to tackle at another time. Logged back in and decided to select my table without values in it. I ran into that problem, so now I really do not know. 
