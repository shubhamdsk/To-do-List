# To-do-List

To Do List Website

This code is a basic implementation of a Todo List using HTML, CSS, and JavaScript.
It uses an array called todos to store the task items.
When a user adds a new task, it creates a new object with the task and completed properties, and then pushes it to the todos array.
When a user clicks on the "Edit" button for a specific task, a prompt appears allowing the user to edit the task's name.
When a user clicks on the "Delete" button, the corresponding task is removed from the todos array.
When a user clicks on the "Completed" button, the corresponding task's completed property is set to true.

The renderTodos() function is responsible for displaying the tasks on the web page.
It clears the existing list of tasks from the HTML (todoList.innerHTML = "") and then iterates over the todos array to create and add HTML elements for each task to the page.
Each task is rendered inside a element, which contains a container for the task text and action buttons.

The localStorage API is used to store and retrieve the todos array in the browser's local storage.
When the page is loaded, it retrieves the stored todos array and renders it on the page.

Overall, this code provides a basic implementation of a Todo List with basic functionality and can be used as a starting point for more complex implementations.
