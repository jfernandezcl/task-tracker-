### Information

You are required to create a task tracker that lets users add new tasks, mark them as complete, or delete them. Completed tasks will be moved to the end of the list and will have strikethrough, and users can unmark tasks to return them to the pending list.
Here is the mockup of the task tracker:

![Descripción de la imagen](/frontend-task/src/images/imagen1.PNG)

### Hint

Store your tasks in an array of objects, where each object represents a task with properties like description and status (completed or not). Whenever a new task is added, updated, deleted, or marked as complete/uncomplete, update the tasks array. Write a function renderTasks which will remove all tasks from the DOM and re-render them based on the updated tasks array
