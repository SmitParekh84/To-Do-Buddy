# To-Do Buddy

![To-Do Buddy](https://github.com/SmitParekh84/Images/blob/main/To-do-Buddy/Screenshot%202024-05-29%20143711.png?raw=true)

To-Do Buddy is a web-based to-do list application that helps you manage your tasks efficiently. It allows you to add, edit, delete, and filter tasks based on their status. The application also includes a theme switcher to customize the look and feel according to your preferences.

## Features

- **Add New Tasks:** Easily add new tasks with optional due dates.
- **Edit Tasks:** Modify existing tasks.
- **Delete Tasks:** Remove tasks that are no longer needed.
- **Mark as Completed:** Toggle the status of tasks between pending and completed.
- **Filter Tasks:** Filter tasks to show all, pending, or completed tasks.
- **Delete All Tasks:** Clear all tasks with a single click.
- **Theme Switcher:** Choose from various themes to personalize the app's appearance.

## Technologies Used

- **HTML5**: For the structure of the web page.
- **CSS3**: For styling, including Tailwind CSS and DaisyUI for utility-first and component-based styles.
- **JavaScript**: For the functionality and interactivity of the application.
- **LocalStorage**: To persist tasks across page reloads.

## Getting Started

### Prerequisites

You need a modern web browser to run this application.

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/todo-buddy.git
   ```

2. Navigate to the project directory:

   ```bash
   cd todo-buddy
   ```

3. Open the `index.html` file in your web browser:

   ```bash
   open index.html
   ```

## Usage

1. **Add a Task**: Enter the task description and optionally select a due date. Click the add button (+) or press Enter.
2. **Edit a Task**: Click the edit button (pencil icon) next to the task, make changes, and click the update button (check icon).
3. **Toggle Task Status**: Click the status button (check icon) to mark a task as completed or pending.
4. **Delete a Task**: Click the delete button (trash icon) next to the task.
5. **Filter Tasks**: Use the filter dropdown to view all, pending, or completed tasks.
6. **Delete All Tasks**: Click the "Delete All" button to remove all tasks.
7. **Change Theme**: Use the theme switcher (palette icon) to select a theme.

## Code Overview

### `index.html`

This file contains the HTML structure and includes links to the CSS files and JavaScript script.

### `css/style.css`

This file contains custom styles for the application, including layout, responsiveness, and theme switcher.

### `js/main.js`

This file contains the JavaScript logic for managing tasks and handling user interactions.

- **TodoItemFormatter**: Formats task details (task description, due date, and status).
- **TodoManager**: Manages the task list, including adding, editing, deleting, and filtering tasks.
- **UIManager**: Manages the user interface, handles user inputs, and updates the task list display.
- **ThemeSwitcher**: Manages theme switching functionality.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any bugs, improvements, or features you'd like to see.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgements

- [Tailwind CSS](https://tailwindcss.com/)
- [DaisyUI](https://daisyui.com/)
- [Boxicons](https://boxicons.com/)

## Author

Made with ❤️ by [Smit Prekh](https://github.com/SmitParekh84)
