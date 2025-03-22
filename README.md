# Simple To Do List Web Application
## Overview
This is a simple and interactive To Do List web application built using HTML, CSS, and JavaScript. It allows users to add tasks, mark them as completed, and delete them. The tasks are saved in the browser's local storage, ensuring that they persist even after the page is refreshed or closed.

---

## Features
* **Add Tasks:** Users can add new tasks by typing in the input box and clicking the "Add" button.
* **Mark as Completed:** Tasks can be marked as completed by clicking on them.
* **Delete Tasks:** Tasks can be deleted by clicking the "×" button next to each task.
* **Persistent Storage:** Tasks are saved in the browser's local storage, so they remain available even after the page is refreshed or closed.

---

## File Structure
* index.html: The main HTML file that structures the To Do List application.
* style.css: The CSS file that styles the application, including the layout, colors, and animations.
* script.js: The JavaScript file that handles the logic for adding, completing, and deleting tasks, as well as saving and retrieving tasks from local storage.
* icon.png: The icon displayed next to the "To Do List" heading.

---

## How to Use
#### Add a Task:
Type your task in the input box.
<br>Click the "Add" button or press Enter.

#### Mark a Task as Completed:
Click on the task you want to mark as completed. The task will be visually marked with a line-through.

#### Delete a Task:
Click the "×" button next to the task you want to delete.

#### Persistent Storage:
All tasks are automatically saved in the browser's local storage. When you revisit the page, your tasks will still be there.

---

## Code Overview
### HTML Structure
* The HTML file (index.html) contains the basic structure of the To Do List application, including the input box, add button, and the list container where tasks are displayed.

### CSS Styling
* The CSS file (style.css) provides the visual styling for the application, including:
* A gradient background for the container.
* Styling for the input box, buttons, and task list.
* Custom checkboxes and delete buttons.

### JavaScript Functionality
* The JavaScript file (script.js) handles the dynamic functionality of the application:
* Adding Tasks: The addTask() function adds a new task to the list.
* Marking Tasks as Completed: Tasks are marked as completed when clicked.
* Deleting Tasks: Tasks are removed from the list when the delete button is clicked.
* Saving and Retrieving Tasks: The saveData() and showTask() functions handle saving tasks to local storage and retrieving them when the page is loaded.

---

## Installation
Clone the Repository:
```
git clone https://github.com/NMHelmy/CS50_FinalProject_Simple-To-Do-List.git
```

Navigate to the Project Directory:
```
cd todo-list
```

Open the Application:
Open the `index.html` file in your preferred web browser.

---

## Customization
* Change the Icon: Replace the icon.png file with your own icon to customize the application's appearance.
* Modify the Styling: Edit the style.css file to change the colors, fonts, or layout of the application.
* Add New Features: Extend the functionality by modifying the script.js file. For example, you could add due dates, priority levels, or categories for tasks.


