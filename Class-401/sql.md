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