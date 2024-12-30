# Todo List App in JavaScript

This project is a simple console-based Todo List application written in JavaScript. It allows users to manage their tasks by adding, viewing, and deleting items interactively. The app runs in a continuous loop until the user decides to quit.

## Features
- **Add Tasks**: Users can add new tasks to the todo list.
- **View Tasks**: Users can view all tasks along with their indices.
- **Delete Tasks**: Users can delete tasks by specifying their index.
- **Interactive Interface**: Requests are taken dynamically using `prompt` until the user chooses to quit.
- **Exit Option**: Users can exit the app gracefully by entering "Quit".

## How It Works
1. The program starts by initializing an empty array `todo` to store tasks.
2. Users are prompted to enter a command (`Add`, `Delete`, `list`, or `Quit`):
   - **`Add`**: Prompts the user to enter a task, which is then added to the todo list.
   - **`list`**: Displays all tasks in the todo list along with their indices. If the list is empty, an appropriate message is shown.
   - **`Delete`**: Prompts the user to enter the index of the task to delete, which is then removed from the list.
   - **`Quit`**: Exits the application with a message.
3. If the user enters an unrecognized command, an error message is displayed.

## Technologies Used
- **JavaScript**: Used for implementing the functionality.
- **Console**: The app runs entirely in the browser console or a Node.js environment.

## Running the App
1. Open your browser's developer tools or a Node.js environment.
2. Paste the code into the console.
3. Follow the prompts to interact with the Todo List app.

## Limitations
- **Input Validation**: The app does not validate user input for proper data types or range. Incorrect inputs may cause unexpected behavior.
- **Persistent Storage**: Tasks are stored in memory and will be lost when the program exits.
