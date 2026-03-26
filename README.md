# To Do App - Task Manager

A simple, visually clean task manager web application built with HTML, CSS, and JavaScript. It allows users to add tasks, mark them as completed, and delete tasks.

## Live Demo

[View Live Demo](https://ahmadubaid061.github.io/to_do_app/)

## Features

- **Add Tasks**: Enter a title and click "Add Task" to create a new task item.
- **Mark as Done**: Click the checkbox next to a task to toggle its completion status. Completed tasks get a greenish background.
- **Delete Tasks**: Click the "Remove" button to permanently delete a task.
- **Responsive Design**: The layout adapts to different screen sizes.
- **Input Validation**: Prevents adding empty tasks.

## Technologies Used

- HTML5
- CSS3 (Grid, Flexbox, custom styling)
- Vanilla JavaScript (DOM manipulation, event handling)

## How to Use Locally

1. Clone the repository:
   ```bash
   git clone https://github.com/ahmadubaid061/to_do_app.git
Navigate to the project folder:

bash
cd to_do_app
Open index.html in your web browser.

Alternatively, you can simply download the index.html file and open it.

# Project Structure
to_do_app/
└── index.html   # Contains all HTML, CSS, and JavaScript
The entire application is contained within a single HTML file, making it easy to deploy and share.

# How It Works
- When you enter a task title and click "Add Task", a new task card is inserted at the top of the list.

- Each task card displays the title, a checkbox for marking completion, and a remove button.

- Checking the checkbox adds a CSS class (.status) to the card, changing its background color.

- Clicking "Remove" deletes the task card from the DOM.

Tasks are stored only in the DOM; refreshing the page will reset the list. This can be extended with localStorage for persistence.

# Potential Enhancements
Add task editing functionality.

- Implement localStorage to persist tasks across page reloads.

- Add due dates and priority levels.

- Improve animations and transitions.

- Filter tasks (All, Active, Completed).

# Author
GitHub: @ahmadubaid061
