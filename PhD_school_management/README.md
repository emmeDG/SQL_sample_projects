## DATABASE FOR GRAD SCHOOL
This projects represents a simple use case of SQL: the creation of a database of relational tables to store all the information related to the organization of a graduate school.
This project should be seen as a sample of my skills with SQL and with the organization of data in a relational database.

### Database organization

The folder `SQL_tables` contains the SQL source files to create the tables of the database. The syntax does not include any specific SQL flavour, so it should work with any.
The tables are the following:

* `proposed_speakers` in `tab_proposed_speakers.sq` - contains the list of all the speakers proposed by the organizers. It includes their ID, complete name, country of origin, and whether they accepted the invite or not;

* `speakers` in `tab_speakers.sq` - contains the list of the confirmed speakers. It inlcudes the contribution_id, the id as their unique identifier from the previous table, the title of their contribution, the topic, the number of allocated slots for their contribution, the number of nights that they are expected to stay at the school;

*`students` in `tab_students.sq` contains the list of the students registered to the school. It includes the student_id, name, last_name, status, affiliation, date of arrival and departure and the total number of nights that they will spend at the school hospitality services;

*`stud_details` in `tab_stud_details.sq` - contains the details of the students which registered to the school. It includes the student_id as unique identifier, their adhesion to the visit to Virgo, any dietary requirements, the preference for a single room and the preferred roommate;

*`topics` in `tab_topic_list.sq` - contains the list of the topics which are expected to be covered by the school;

*`costs` in `tab_costs.sq` - contains a list of the per capita costs foreseen for each service to establish the total cost of the school through queries.
