## DATABASE FOR GRAD SCHOOL
This projects represents a simple use case of SQL: the creation of a database of relational tables to store all the information related to the organization of a graduate school.
This project should be seen as a sample of my skills with SQL and with the organization of data in a relational database.

### Database organization

The folder 'SQL_tables' contains the SQL source files to create the tables of the database. The syntax does not include any specific SQL flavour, so it should work with any.
The tables are the following:

* ’proposed_speakers’ in ’tab_proposed_speakers.sq’ - contains the list of all the speakers proposed by the organizers. It includes their ID, complete name, country of origin, and whether they accepted the invite or not;
* ’speakers’ in ’tab_speakers.sq’ - contains the list of the confirmed speakers. It inlcudes the contribution_id, the id as their unique identifier from the previous table, the title of their contribution, the topic, the number of allocated slots for their contribution, the number of nights that they are expected to stay at the school. 
