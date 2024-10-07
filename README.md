
---

# School and Manager System

This Python project is designed to simulate a simple school management system. The system includes two classes:
- `school` class: Represents a school branch with a teacher, department, and student capacity.
- `manager` class: Extends the `school` class and adds a managerial role with a title (e.g., CTO).

## Features

### `school` Class
- **Attributes**: 
  - `branch`: Name of the school branch.
  - `teacher`: Name of the teacher in charge.
  - `department`: The department assigned to this branch.
  - `avaliable`: Number of available students.
  
- **Methods**:
  - `show_info()`: Displays the details of the school branch, including the teacher, department, and available student capacity.
  - `teacher_name()`: Prints the name of the teacher assigned to the branch.
  - `depart_change()`: Allows the user to change the department of the branch and displays the updated information.

### `manager` Class
- **Attributes**:
  - Inherits all attributes of the `school` class and adds:
  - `title`: The managerial title of the person (e.g., CTO).

- **Methods**:
  - Overrides `show_info()` to display additional information specific to the manager's role (title).

## How to Run the Program

1. Create an instance of the `manager` class with the following parameters:
   - `branch`: The name of the school branch.
   - `teacher`: The name of the teacher.
   - `department`: The assigned department.
   - `avaliable`: The number of available students in that branch.
   - `title`: The managerial title (e.g., CTO).

2. Call the `show_info()` method to print the school and manager details.

3. Use the `depart_change()` method to change the department of the school.

Example usage:

```python
director = manager("11", "Emre", "Tech", "55", "CTO")
director.show_info()
director.depart_change()
```

## Planned Features
- Add a user interface to dynamically add, remove, and modify branches and their information.
- Extend the class structure to support more roles like `Student` and `Principal`.

## How to Contribute
- Fork the repository and create a new feature branch.
- Submit a pull request with a detailed description of your changes.
- Feel free to suggest improvements or report bugs!

## License
This project is open source and available under the [MIT License](LICENSE).

---

