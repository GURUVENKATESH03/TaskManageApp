# TaskManageApp
# Task Management Application

## Project Overview

The Task Management Application allows users to manage tasks by providing functionalities to add, edit, delete, view, and mark tasks as completed or pending. This application utilizes JavaScript for front-end functionality, with HTML and CSS to structure and style the user interface.

## Key Features

- **Add Task**: Users can input a task name and description.
- **View Tasks**: Display a list of all tasks with their details.
- **Edit Task**: Users can edit the details of an existing task.
- **Delete Task**: Users can remove a task from the list.
- **Task Status**: Users can mark tasks as completed or pending.
- **Filter Tasks**: Users can filter tasks based on their status (completed/pending).

## Requirements

### HTML Structure
- Create a simple layout with input fields for task name and description.
- Buttons for adding, editing, and deleting tasks.
- A section to display the list of tasks.

### CSS Styling
- Basic styling to make the application user-friendly.
- Responsive design to ensure it works on different screen sizes.

### JavaScript Functionality
- Use ES6+ features (let, const, arrow functions, template literals, etc.).
- Implement functions for adding, editing, deleting, and filtering tasks.
- Use event listeners to handle user interactions (e.g., button clicks).
- Store tasks in an array (instead of using local storage in this version).
- Display tasks dynamically on the page based on the current state of the tasks array.

### Error Handling
- Validate user input (e.g., ensure task name is not empty).
- Provide user feedback for successful or failed operations.

## Optional Features

- **Due Dates**: Add due dates for tasks and sort tasks based on due dates.
- **Search Feature**: Implement a search feature to find tasks by name.
- **Asynchronous Operations**: Use Promises or async/await for any asynchronous operations (if applicable).

## Concepts Covered

- **Variables and Data Types**: Using `let`, `const`, and different data types (e.g., arrays, strings).
- **Functions**: Creating and using functions, including arrow functions.
- **Objects and Arrays**: Working with objects (Task) and arrays (task list).
- **DOM Manipulation**: Adding, removing, and updating elements in the DOM.
- **Event Handling**: Using event listeners to respond to user actions (e.g., button clicks).
- **Error Handling**: Validating user input and providing feedback.

## How to Run the Application

1. **Clone the Repository**:
    - Open your terminal and run the following command:
    ```bash
    git clone https://github.com/your-username/task-management-app.git
    ```

2. **Navigate to the Project Directory**:
    ```bash
    cd task-management-app
    ```

3. **Open `index.html` in your Browser**:
    - Simply open the `index.html` file in any web browser (Chrome, Firefox, etc.) to start using the application.

## Application Features Walkthrough

1. **Add Task**: 
   - Click on the "Add" button to open the input form.
   - Enter the task name and click "Add Task" to add it to the list.

2. **View Tasks**:
   - Click on the "View Task" button to see a list of all tasks.

3. **Edit Task**:
   - Click the "Edit" button next to a task to modify its content.

4. **Delete Task**:
   - Click the "Delete" button next to a task to remove it from the list.

5. **Task Status**:
   - Tasks can be marked as completed or pending (future update).

## Example of a Task:

- Task Name: "Finish Homework"
- Description: "Complete the JavaScript assignment by tomorrow."

## Submission Guidelines

- The project should be completed within 5 days.
- Code should be well-commented and organized.
- A `README` file should be included, explaining how to run the application and any additional features implemented.
- The project should be hosted on GitHub and a link should be provided for review.

## Technologies Used

- HTML5
- CSS3
- JavaScript (ES6+)
- DOM Manipulation

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

### Acknowledgements

- Inspired by simple task management tools.
- Open-source tutorials for building similar web applications.

---

Feel free to contribute to this repository. Open an issue if you encounter any bugs or want to suggest improvements!

