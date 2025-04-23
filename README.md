# KanBan Board Pro
Basic KanBan board used to track tasks. 


## Description

Kanban Task Tracker Pro is a web-based application designed to help users organize their workflow efficiently using a visual Kanban board. It allows users to create tasks, assign priorities, set due dates, break down tasks into subtasks, and track progress across different stages (To Do, In Progress, Done). The application utilizes modern web technologies and provides a clean, interactive, and responsive user interface. Data is persisted locally in the browser using Local Storage.

## Features

* **Kanban Board:** Visual drag-and-drop interface with three columns: To Do, In Progress, and Done.
* **Task Creation:** Easily add new tasks with descriptions and assign priorities (High, Medium, Low, None).
* **Subtasks:** Break down complex tasks into smaller, manageable subtasks.
* **Due Dates:** Assign due dates to tasks using a date picker.
* **Priority Indicators:** Visually distinguish tasks based on their priority level.
* **Inline Editing:** Edit task descriptions directly on the card.
* **Subtask Management:** Add, delete, and mark subtasks as complete/incomplete.
* **Progress Tracking:** View subtask completion progress on the task card and in the details modal.
* **Task Details Modal:** View comprehensive details for each task, including status, priority, dates, and subtask list.
* **Search Functionality:** Filter tasks and subtasks based on keywords in their descriptions.
* **Statistics:** View key metrics like total tasks, completed tasks, and overall subtask completion percentage.
* **Data Persistence:** Tasks are saved in the browser's Local Storage, so your work persists across sessions.
* **Import/Export:**
    * Export all task data to a JSON file.
    * Import tasks from a JSON file (replaces existing tasks).
* **Task Analytics Table:** View all tasks and subtasks in a sortable, filterable table format.
* **Table Actions:**
    * Export table data to a CSV file.
    * Clear all tasks from the board and storage.
* **Confetti Celebration:** A fun confetti effect triggers when a task is moved to the "Done" column.
* **Responsive Design:** Adapts to different screen sizes (desktop, tablet, mobile).

## How to Use

1.  **Open the `index.html` file** in your web browser.
2.  **Add Tasks:** Use the "Create New Task" form at the top. Enter the task description, select a priority, and click "Add Task".
3.  **Manage Tasks:**
    * **Drag & Drop:** Click and drag tasks between the "To Do", "In Progress", and "Done" columns.
    * **Edit Text:** Click directly on the task text on a card to edit it. Press Enter or click outside the text area to save.
    * **Set Due Date:** Click the date input on a task card to select a due date.
    * **View Details:** Click the eye icon (<i class="fas fa-eye"></i>) on a task card to open the details modal.
    * **Delete Task:** Click the '×' button on a task card to delete it (confirmation required).
4.  **Manage Subtasks:**
    * **Add:** Enter subtask text in the input field at the bottom of a task card and click "Add".
    * **Complete/Incomplete:** Check/uncheck the checkbox next to a subtask.
    * **Delete:** Click the '×' button next to a subtask.
5.  **Search:** Use the search bar to filter tasks based on text in the task or subtask descriptions.
6.  **Analytics Table:** Scroll down to view the detailed table of all tasks and subtasks. Click on a row to view the parent task's details in the modal. Use the "Actions" dropdown for CSV export or clearing all tasks.
7.  **Import/Export:** Use the "Import" and "Export" buttons in the header to save/load your task data as a JSON file.

## Technologies Used

* **HTML5:** Structure of the web page.
* **CSS3:** Styling, including custom properties and gradients.
* **Tailwind CSS:** Utility-first CSS framework for rapid UI development and responsive design.
* **JavaScript (ES6+):** Application logic, DOM manipulation, event handling, drag-and-drop functionality, Local Storage interaction.
* **Font Awesome:** Icons.
* **Google Fonts (Inter):** Typography.
* **Canvas Confetti:** Library for the confetti celebration effect.

## Potential Future Enhancements

* User Accounts & Cloud Storage (e.g., Firebase)
* Collaboration features (multiple users, assignments)
* Task tagging/categorization
* Reminders/Notifications for due dates
* More advanced filtering and sorting options (by priority, due date)
* Themes/Customization options
* Integration with calendar applications
* Archiving completed tasks instead of just keeping them in "Done"
