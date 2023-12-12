# ToDo Application with Redux

This is a simple ToDo application built using React and Redux to manage the global state. The application allows users to add new tasks, filter tasks by their completion status (done/not), and edit existing tasks.

## Components

### AddTask

This component provides a text input and a button to add a new task. When the user enters a task description and clicks the "Add Task" button, a new task is added to the list.

### ListTask

This component displays the list of tasks based on the selected filter (all/done/not done). It uses the Redux state to dynamically update the task list based on the user's filter selection.

### Task

Each task is represented by this component, displaying the task description. Users can click on a task to toggle its completion status (done/not done) and click the "Edit" button to modify the task description.

## Actions and Reducer

- `addTask`: Adds a new task to the list.
- `toggleTask`: Toggles the completion status of a task.
- `editTask`: Edits the description of a task.
- `setFilter`: Sets the filter for displaying tasks (all/done/not done).

