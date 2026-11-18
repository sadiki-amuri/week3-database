# week3-database

CREATE TABLE student (
    id INT PRIMARY KEY,
    fullName VARCHAR(100),
    age INT
);

INSERT INTO student (id, fullName, age)
VALUES 
    (1, 'Alice Wanjiku', 19),
    (2, 'Brian Otieno', 18),
    (3, 'Cynthia Mwangi', 21);

UPDATE student
SET age = 20
WHERE id = 2;
