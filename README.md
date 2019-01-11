# UniDatabases
Database assignment using PostgresSQL

Database is able to be used under a business scenario.
Stores:
-Clients
-Client info
-Work Orders
-Work Logs
-Refusals
-Outdated logs
-Employees
-Employee info

ER is not fully normalised. Made more sense not to normalise the client tables as was neater to push fax,phone and email into one with a check constraint.
