# Project-Proposal
My final project will be a visual, interactive task tracker created using the p5.js editor. The user will be able to:

Add tasks through a simple input system.

See a list of tasks rendered on the canvas.

Mark tasks as complete with a click.

Delete tasks if desired.

See completed tasks get visually updated (e.g., strikethrough or color change).

The interface will be minimalist but functional, relying on custom classes and interactive elements drawn with p5.js.

 What I Hope to Learn
Through this project, I aim to:

Deepen my knowledge of abstraction by creating custom classes like Task and TaskManager.

Practice building interactive interfaces using the p5.js canvas, including mouse input and dynamic rendering.

Get comfortable with modular code, by creating helpful utility functions with well-designed parameters and return values.

Develop a clearer understanding of iteration and conditionals as I manage task lists and handle input events.

Experience iterative development, using GitHub for version control and documentation.

 Technical Design 
Classes:

Task: Stores task text, status (complete or not), and position on screen.

TaskManager: Manages all tasks in an array, handles adding, deleting, marking complete.

Functions:

addTask() – Adds a new task from user input.

drawTasks() – Loops through tasks and draws them on screen.

mousePressed() – Checks for interaction with tasks (e.g., to mark complete or delete).

saveTasks() / loadTasks() – (Optional stretch goal) save tasks using localStorage.

Core Concepts Used:

Variables and data structures (arrays)

Abstraction (classes and modular functions)

Iteration and conditionals (looping through and checking tasks)

Event-driven interaction (mouse clicks, input fields)

Troubleshooting
I will commit frequently on GitHub with descriptive messages (e.g., "Implemented Task class", "Fixed bug in mouse click logic").

Any bugs or unexpected behavior will be documented in a NOTES.md or via GitHub issues, along with how I resolved them.

I will test if it works as I go

