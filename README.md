USE Department

[CREATE TABLE Employee(
employee_id INT PRIMARY KEY,
employee_name VARCHAR(100),
);

CREATE TABLE Departments(
department_id INT PRIMARY KEY,
department_name VARCHAR(100),
manager_id INT,
);

INSERT INTO employee(employee_id, employee_name)
(1, 'John Doe'),
(2, 'Jane Doe')


INSERT INTO departments(department_id, department_name, manager_id)
(1, 'IT',),
(2, 'HR',)



SELECT * FROM Employee
](https://onecompiler.com/mysql/44dyum2ms)
