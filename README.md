# Guide to Repository

## Milestones Folder

Milestones are a way for our group to track progress and get certain key things done before specific deadlines. Although these were included in the repository for grading purposes, they also help illustrate the process taken to reach the current stage of this project. Descriptions of each file are provided below.

### Milestone 1

In this milestone, entities, attributes, and business rules were defined.  
The included PNG file contains the entity relationship model for the entities and attributes used to develop this project.  
> Note: This is only the first draft of the relationship model.

### Milestone 2

This milestone includes a relational schema showing the organized tables for each entity and attribute.  
ID attributes are underlined in each table.  
> Note: This was an early stage in the database development, and many tables and attributes are now outdated.

### Milestone 3

This milestone focuses on identifying user roles and their permissions (Create, Read, Update, Delete).  
Flowcharts are included to represent how data flows and the necessary checkpoints.  
Some sketches of the user interface were also designed as a starting point for the final website.

### Milestone 4

SQL `CREATE` statements were used to build the database tables in this milestone.  
In the file `database create.sql`, the following tables are created:

- `resources`
- `individuals`
- `services`
- `needs`

`INSERT` statements with mock data follow the table definitions.  
The file `Relational schema.jpg` contains the updated relational schema that reflects the final structure.

---

## Flaskapp Folder

- `app.py`  
  Main application file.

- `Data.sql`  
  Similar to Milestone 4, used for inserting mock data into the tables for testing.

- `models.py`  
  Contains the model definitions for the database.

- `Python queries.sql`  
  SQL queries used within the Python environment.

- `Python translation.sql`  
  SQL translation scripts.

- `Requirements.txt`  
  Lists Python dependencies required to run the application.

- `Reset-from-peewee.sh`  
  Shell script to reset the database using Peewee ORM.

- `reset-from-sql.sh`  
  Shell script to reset the database using raw SQL.

- `sqlscript.py`  
  Python script for executing SQL scripts.

- `Tables.sql`  
  Contains the final versions of all tables with defined attributes, keys, and data types.
