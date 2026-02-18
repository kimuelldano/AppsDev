CREATE TABLE Employee (
    employee_id INT AUTO_INCREMENT PRIMARY KEY,
    employee_name VARCHAR(100) NOT NULL
);

CREATE TABLE Departments (
    department_id INT AUTO_INCREMENT PRIMARY KEY,
    department_name VARCHAR(100) NOT NULL,
    manager_id INT,
    FOREIGN KEY (manager_id) REFERENCES Employee(employee_id)
);

INSERT INTO Employee (employee_name) VALUES
('John Doe'),
('Jane Doe');

INSERT INTO Departments (department_name, manager_id) VALUES
('IT', 1),
('HR', 2);

SELECT * FROM Employee;
SELECT * FROM Departments;
