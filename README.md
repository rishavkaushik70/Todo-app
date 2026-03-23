# Vanilla JS To-Do List

A clean, responsive, and lightweight To-Do list web application built entirely with HTML, CSS, and Vanilla JavaScript. This project serves as a strong foundation in DOM manipulation, event handling, and browser storage.

## Live Demo
https://todo-app-rishavkaushik.netlify.app/

## Key Features
* **Create & Manage Tasks:** Users can easily add new tasks to their daily list. Includes validation to prevent adding empty tasks.
* **Mark as Complete:** Click on any task to toggle its completion status (visualized with a checkmark and strikethrough).
* **Delete Tasks:** Remove individual tasks seamlessly using the '×' button.
* **Data Persistence:** Utilizes the browser's native `localStorage` API. Your tasks remain saved even if you refresh the page or close the browser.
* **Keyboard Accessibility:** Enhances user experience by allowing task submission using the `Enter` key.

## Tech Stack
* **Markup & Styling:** HTML5, CSS3 (Custom UI with a modern gradient background)
* **Scripting:** Pure Vanilla JavaScript (ES6+)
* **Storage:** Web Storage API (`localStorage`)

## Technical Learnings & Practices
During the development of this application, I implemented several core JavaScript concepts:
* **DOM Manipulation:** Creating, appending, and removing HTML elements dynamically (`createElement`, `appendChild`, `remove`).
* **Event Delegation:** Instead of adding event listeners to every single list item, I attached a single listener to the parent container to optimize performance.
* **State Persistence:** Converting DOM structures to string format to save in `localStorage` and retrieving them on page load.

## How to Run Locally
Since this is a static project with no external dependencies, running it is incredibly simple:

1. Clone the repository:
   ```bash
   git clone [https://github.com/rishavkaushik70/Todo-app.git](https://github.com/rishavkaushik70/Todo-app.git)
