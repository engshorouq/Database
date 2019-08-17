# :stars: Database

## What is database :thinking: ?
- A database is a data structure that stores organized information. Most databases contain multiple tables, which may each include several different fields.

- A database is a collection of related information stored in one or more computer files in an organized fashion. Normally the information or data is organized into tables. The information in a table is organized in such a way that it can easily be updated, sorted, corrected, and filtered.

-  a set of related data and the way it is organized. Access to this data is usually provided by a "database management system" (DBMS) consisting of an integrated set of computer software that allows users to interact with one or more databases and provides access to all of the data contained in the database (although restrictions may exist that limit access to particular data). The DBMS provides various functions that allow entry, storage and retrieval of large quantities of information and provides ways to manage how that information is organized.

## Types of database : 
- Centralised database.
- Distributed database.
- Personal database.
- End-user database.
- Commercial database.
- NoSQL database.
- Operational database.
- **`Relational database`**.
- Cloud database.
- Object-oriented database.
- Graph database.

### **Relational Database :**

**Relationships :** are a logical connection between different tables, established on the basis of interaction among these tables.

**Relational database model :** This model organizes data into one or more `tables` (or "relations") of `columns` and `rows`, with a unique key (`primary key`) identifying each row. `Rows` are also called `records` or `tuples`. `Columns` are also called `attributes`. Generally, each table/relation represents one "entity type" (such as customer or product). The rows represent instances of that type of entity and the columns representing values attributed to that instance.

**Example :**

![img](https://www.w3resource.com/w3r_images/component-of-a-database-table.gif)

**Relationship between tables :**

- **primary key :** A table typically has a column or combination of columns that contain values that uniquely identify each row in the table.

- **foreign key :** 
    - linked  to a primary key constraint in another table; - linked to columns of a UNIQUE constraint in another table.
    - reference only tables within the same database on the same server. Cross-database referential integrity must be implemented through triggers.
    - an reference another column in the same table. This is referred to as a self-reference.

- **Type realtionship** :
    - One-to-one relationships: When there’s only one instance of Entity A for every instance of Entity B

    - One-to-many relationships: These relationships occur when a record in one table is associated with multiple entries in another

    - Many-to-many relationships: 
        - When multiple entities from a table can be         associated with multiple entities in another table, they are said to have a many-to-many relationship.

        - But Relational database systems (RBBS) usually don't allow you to implement a direct many-to-many relationship between two tables.

        - To avoid this problem, you can break the many-to-many relationship into two one-to-many relationships by using a third table, called a join table as in the picture

         ![many-to-many](https://fmhelp.filemaker.com/help/18/fmp/en/FMP_Help/images/relational.07.06.1.png)



   - **example :**
   
    ![relationship](https://i0.wp.com/3.bp.blogspot.com/-UDSw40EeO7E/VrgkoQtRSfI/AAAAAAAAAXA/R5xhNxFV46w/s400/database-mapping-coordinalities.jpg?resize=400%2C303&ssl=1)

**Advatages :**
- enable users to easily categorize and store data that can later be queried and filtered to extract specific information for reports.

- Accuracy: Data is stored just once, eliminating data deduplication.

- Flexibility: Complex queries are easy for users to carry out.
- Collaboration: Multiple users can access the same database.
- Trust: Relational database models are mature and well-understood.
- Security: Data in tables within a RDBMS can be limited to allow access by only particular users.

## Database Queries :
- A database query extracts data from a database and formats it in a readable form. A query must be written in the language the database requires; usually, that language is Structured Query Language (SQL).

- Queries are one of the things that make databases so powerful. A "query" refers to the action of retrieving data from your database. Usually, you will be selective with how much data you want returned. If you have a lot of data in your database, you probably don't want to see everything. More likely, you'll only want to see data that fits a certain criteria.





