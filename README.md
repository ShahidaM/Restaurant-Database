# Restaurant-Database

CASE STUDY:
Burger Shack is a franchise with a chain of restaurants around Ireland. The franchise owners want to
launch a web app where customers can book tables and check their receipts. This web app will also be
accessed by the restaurant manager and will present details on customers, waiting staff and managers at
every restaurant branch around the country.
Each Burger Shack restaurant has a unique numeric restaurant identifier, address and phone number.
Customers who wish to book a table can either make a booking online, by phone or walk into one of the
restaurants and talk to a manager who can complete the table booking on the web app.
When a customer books a table at any Burger Shack restaurant, they must provide the following
information: their name, address, and email address, each of which will be stored and cannot be missing.
The customer must also provide their age, which must be over 18. The customer is assigned a unique
identifier – the customer number.
The main customer making the booking is also assigned a booking receipt, which includes a booking ID
number and details of the time of the table booking and the number of people at the table. Burger
Shack only allows booking tables for up to 8 (eight) people. A customer can have many bookings with
Burger Shack, but each booking is for one customer.
Each table in every restaurant has a unique number and details of the type of table and its location in
the restaurant. There are four types of tables (2, 4, 6 and 8 seater) and 2 locations (window or interior).
The owners of Burger Shack are still worried that the pandemic of COVID-19 might return, so they want
to keep customers’ details on the database for contact tracing. When the party arrive at the restaurant,
they are shown to their table and details of each person at the table must be recorded and stored in the
database. The table number, name, email address, and phone number of every other guest (apart from
the main customer who has already given this information) must be provided.
The details of the waiter and manager who served the table must also be recorded. Burger Shack Staff
are assigned to a particular restaurant branch, their location is stored as part of their employment
record. All restaurant staff have a unique identifier. Their name, address, phone number, email address,
date of birth and start date of employment at Burger Shack are also stored. All staff email addresses
must be their company email (ending with @burgershack.com).

INSTRUCTIONS:
1. You must generate statements to create the tables based on your data modelling. Tables,
attributes, data types and other constraints must match your model (including naming).
2. You must generate data to populate your tables to fulfil the queries required and create the insert
statements to achieve this.
 Provide at least 5 (five) rows per table.
 Data should be persisted.
 You need to be careful with the data you choose to insert. You must ensure that the queries
you design will result in data being returned for all the queries/alterations you are asked to do.
3. You are required to provide SQL statements to demonstrate the following:
 One UPDATE or one DELETE combined with a subquery.
 One query using a selection function (CASE/DECODE)
 One INNER join using a GROUP Function
 One LEFT OUTER Join
 One RIGHT OUTER Join (using different tables to your left outer join)
 One UNION
 One INTERSECT
 One VIEW
Use the commenting SQL syntax to demonstrate how you implemented each query.
