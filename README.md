
-- Question 1: Create student table
CREATE TABLE student (
    id INT PRIMARY KEY,
    fullName VARCHAR(100),
    age INT
);

-- Question 2: Insert records
INSERT INTO student (id, fullName, age)
VALUES
(1, 'Amina', 19),
(2, 'Brian', 18),
(3, 'Fatuma', 21);

-- Question 3: Update student age
UPDATE student
SET age = 20
WHERE id = 2;

-- Display all records
SELECT * FROM student;
