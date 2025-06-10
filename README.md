# JOIN-PRACTICE

*COMPANY*: CODTECH IT SOLUTIONS

*NAME*: REKHARANI SUBUDHI

*INTERN ID*: CT04DF1188

*DOMAIN*: SQL

*DURATION*: 4 WEEKS

*MENTOR*: NEELA SANTOSH

##In this TASK, I have demonstrated my understanding of various types of SQL join operations using MySQL Workbench, a powerful tool for database design, management, and SQL development. The objective of this task was to create and manipulate relational database tables, simulate real-world data scenarios, and apply different types of SQL joins such as INNER JOIN, LEFT JOIN, RIGHT JOIN, FULL JOIN, SELF JOIN, and their exclusive variants. This was part of my internship training where I focused on improving my database and SQL querying skills through hands-on practice.

To begin with, I created a database named company and designed two relational tables: student and course. The student table consists of student IDs and names, while the course table contains course IDs and course names. The id column serves as the primary key in both tables to maintain data integrity and consistency. After successfully creating and inserting sample data into these tables, I used several SQL join operations to retrieve meaningful insights by combining data from the two tables.

The INNER JOIN operation was used to extract records where matching id values exist in both student and course tables. This type of join is helpful when we need to fetch only the intersecting data between two datasets. Next, I used the LEFT JOIN, which returns all records from the student table and the matching records from the course table. It is particularly useful for identifying students who are not enrolled in any course, as unmatched rows from the course table return NULL.

Similarly, the RIGHT JOIN retrieves all records from the course table, regardless of whether there is a corresponding student. This is beneficial for recognizing courses that are not currently assigned to any student. For a more comprehensive view, I implemented the FULL OUTER JOIN by combining both LEFT JOIN and RIGHT JOIN with a UNION operator. Since MySQL does not directly support FULL OUTER JOIN, this approach helps to display all records from both tables, including unmatched rows.

I then explored exclusive joins to fetch only the unmatched data. The LEFT EXCLUSIVE JOIN returns students who do not have any corresponding course, while the RIGHT EXCLUSIVE JOIN returns courses that are not assigned to any student. The FULL EXCLUSIVE JOIN is the union of both, providing a complete picture of unmatched records across both tables.

In addition to basic joins, I created another table named employee to demonstrate the use of SELF JOIN. This table includes employee IDs, names, and manager IDs. The SELF JOIN was performed to establish a hierarchical relationship between employees and their managers. This query helped identify which employee is reporting to which manager, simulating a real-world organizational structure.

This TASK not only allowed me to revise and apply theoretical knowledge but also helped me develop practical skills in relational database management. I learned how to write efficient SQL queries, use aliases, understand different join types, and visualize data relationships clearly. It also deepened my understanding of how businesses use database systems to store, retrieve, and analyze data effectively. MySQL Workbench proved to be a great platform for testing, debugging, and executing queries smoothly. This project reflects my ability to apply foundational database concepts in solving practical problems and will serve as a reference for similar database-driven applications in the future.

#OUTPUTS

![Image](https://github.com/user-attachments/assets/81656d03-0258-465a-8e92-32f293de4798)

![Image](https://github.com/user-attachments/assets/a53e76f6-4485-4ce5-ba03-cb97eb8ec6da)

![Image](https://github.com/user-attachments/assets/7d2b7eb5-3a80-4a15-8d47-61ee05f431ad)

![Image](https://github.com/user-attachments/assets/5d906c1a-bb8d-4e15-8994-b763555bbe58)

![Image](https://github.com/user-attachments/assets/2aee6156-fdc0-4ca6-97d5-fcc8cb64bfe5)

![Image](https://github.com/user-attachments/assets/2dee4dad-14b1-4484-86c6-acd0c9906c0a)

![Image](https://github.com/user-attachments/assets/c7b6d779-b853-4638-b53d-06255ce880c9)

![Image](https://github.com/user-attachments/assets/15c25b4b-aa31-46b8-873c-7c27a1347f3e)





