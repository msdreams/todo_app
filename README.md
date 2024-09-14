Description:
This Todo App is a modern task management application showcasing my frontend development skills and API integration.
The app is built using React, TypeScript, and SCSS, providing a user-friendly interface for adding, editing, deleting, and managing task statuses.

Technologies:
React: Used to create dynamic and responsive components.
TypeScript: Ensures strong typing and improved code maintainability.
JavaScript (ES6+): Applied for application logic and state management.
SCSS (BEM): Modular CSS structure for better scalability and maintainability.
API: Integrated with a server to manage tasks via asynchronous requests.
LocalStorage: Utilized for persisting task data locally between user sessions.
Key Features:
Add and Delete Tasks: Users can easily add new tasks and delete unnecessary ones.
Task Status Toggling: Users can toggle a task’s status (completed/incomplete) with a loading indicator displayed while waiting for an API response.
Toggle All Tasks: Implemented a button to toggle the status of all tasks, which works similarly to individual task updates.
Edit Task Title: Users can edit a task title on double-click, with changes saved on pressing Enter or losing focus.
Error Handling: Error messages are shown in case of API failures during task updates, deletion, or status changes.
Loader Indicator: A loader overlay is displayed during API calls, indicating that the request is being processed.
Major Implementations:
Task Status Toggling with API: The task’s status is updated only upon successful API response, with error notifications in case of failure.
Bulk Task Status Update: A toggleAll button is implemented to change the status of all tasks, simulating multiple individual updates for improved performance.
Task Title Editing: Users can edit task titles with automatic saving, cancellation on empty input, and error handling for API issues.
Why This Project Matters:
This project highlights my skills in integrating a frontend application with external APIs, managing state with React, handling asynchronous data, and ensuring a smooth UX. TypeScript enhances code quality and safety, while loaders and notifications improve user interaction.

[Deploy] https://msdreams.github.io/todo_app/
