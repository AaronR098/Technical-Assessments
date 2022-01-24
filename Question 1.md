# Endpoint Documentation

---

## get_employee
**Parameters**: Employee ID
<br />

**Method**: Get
<br />

**Return**: Takes an employee id and returns the name, department_name, and salary of the employee in a JSON object.

---

## add_employee
**Parameters**: Employee Name, Salary, Department_id
<br />

**Method**: Post
<br />

**Return**: Populates data in each table accordingly and returns uses the get_employee functionality to return the employee JSON object (as outlined in the row above).

---

## add_department
**Parameters**: Department Name
<br />

**Method**: Post
<br />

**Return**: Takes a department name and creates a new department. Returns the new department and its id.

---

## update_salary
**Parameters**: Employee Name, New Salary 
<br />

**Method**: Put
<br />

**Return**: Takes employee_id and new salary. Returns employee JSON object from get_employee.

---

## terminate_employee
**Parameters**: Employee Id
<br />

**Method**: Delete
<br />

**Return**:Takes employee_id and deletes their employee and salary entities in the database.

