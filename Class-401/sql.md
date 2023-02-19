# reading-notes for code 401

My reading notes for **SQL**


SELECT column, another_column, …
FROM mytable;

SELECT column, another_column, …
FROM mytable
WHERE condition
    AND/OR another_condition
    AND/OR …;

SELECT DISTINCT column, another_column, …
FROM mytable
WHERE condition(s)
ORDER BY column ASC/DESC
LIMIT num_limit OFFSET num_offset


INNER JOIN newtable
   ON oldtable.id = newtable.id


INSERT INTO table
(id, blah, blah2)
VALUES (1, "yes", 55);


UPDATE mytable
SET column = value_or_expr, 
    other_column = another_value_or_expr, 
    …
WHERE condition;


DELETE FROM mytable
WHERE condition;


CREATE TABLE IF NOT EXISTS mytable (
    column DataType TableConstraint DEFAULT default_value,
    another_column DataType TableConstraint DEFAULT default_value,

ALTER TABLE mytable
ADD column DataType OptionalTableConstraint 
    DEFAULT default_value;

![lesson 1](/assets/lesson-1.png)
![lesson 2](/assets/lesson-2.png)
![lesson 3](/assets/lesson-3.png)
![lesson 4](/assets/lesson-4.png)
![lesson 5](/assets/lesson-5.png)
![lesson 6](/assets/lesson-6.png)
![lesson 13](/assets/lesson-13.png)
![lesson 14](/assets/lesson-14.png)
![lesson 15](/assets/lesson-15.png)
![lesson 16](/assets/lesson-16.png)
![lesson 17](/assets/lesson-17.png)
![lesson 18](/assets/lesson-18.png)