# DATABASE-Week3
Database R/ship assignment 
Student:Bismark Kiprotich.
1. **One-to-One (1:1) Relationship:**
   - In a One-to-One relationship, each record in one table is associated with exactly one record in another table, and vice versa.
   - This relationship is relatively rare in database design, as it's often more efficient to combine the related data into a single table.
   - An example of a One-to-One relationship could be a relationship between a "Person" table and a "Passport" table, where each person has exactly one passport.

2. **One-to-Many (1:N) Relationship:**
   - In a One-to-Many relationship, each record in the "one" table can be associated with multiple records in the "many" table, but each record in the "many" table is associated with only one record in the "one" table.
   - This is one of the most common types of relationships in database design.
   - An example of a One-to-Many relationship could be a relationship between an "Order" table and an "Order Details" table, where each order can have multiple order details.

3. **Many-to-Many (M:N) Relationship:**
   - In a Many-to-Many relationship, each record in one table can be associated with multiple records in another table, and vice versa.
   - This type of relationship requires a junction table (or associative table) to facilitate the connection between the two related tables.
   - An example of a Many-to-Many relationship could be a relationship between a "Student" table and a "Course" table, where each student can enroll in multiple courses, and each course can have multiple students.
Each of these types of relationships serves different purposes and is used to model different kinds of associations between entities in a database. Understanding these relationships is fundamental to designing efficient and effective database schemas.
