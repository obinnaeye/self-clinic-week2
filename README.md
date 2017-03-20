# A screenshot showing the relationship between two simple data tables.

## Problem Statement: Create a register for students in a given secondary school. From the register, the user should be able to obtain the list of all school prefects.

## Explanation of Diagram: 
1. The "Students" table holds the list of all students in the given school. The primary key here is the "reg_number". The data types explain what type of data each name variable should hold. For example, "reg_number" is a VARCHAR data type; which is a combination of strings and numbers.

2. The "School Prefects" table holds the list of all school prefects. The "reg_number" here is a foreign key, connecting this table to the "Students" table.