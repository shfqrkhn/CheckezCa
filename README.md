# CheckerCa - Advanced Checklist Manager

Online demo: https://shfqrkhn.github.io/CheckezCa/

## Overview

CheckerCa is a single-file HTML/CSS/JS app for hierarchical checklists. Uses Bootstrap 5 & `localStorage`. Features rich tasks, sub-tasks, sorting, search/filter, progress tracking, and JSON import/export.

## Key Features

* **Hierarchical Tasks:** Nested sub-tasks with properties (status, priority, due date, notes, tags, etc.).
* **Customization & Sorting:** Nameable checklists; sort by Default, Priority, Due Date, Alphabetical, Status.
* **Dynamic UI:** Expand/collapse, client-side search/filter.
* **Persistence:** All data saved in `localStorage`.
* **Data I/O:** Named JSON import/export.
* **Feedback & Accessibility:** Modals, visual cues (status, priority, overdue), item animations, ARIA support, keyboard shortcuts (`Alt+N` new item, `Ctrl+/` search).
* **Utilities:** Print view, "Last Saved" timestamp, "Scroll to Top", "Confirm on Unload".

## Tech Stack

* HTML5, CSS3, Vanilla JavaScript (ES6+)
* Bootstrap 5 (CDN), Bootstrap Icons (CDN)
* `localStorage`

## Usage

1.  **Open `index.html`** in a browser.
2.  **Manage:** Name checklist, use "+Item" (`Alt+N`), sort, filter (`Ctrl+/`), import/export/print.

## JS Structure

* **`DataManager`:** Data logic, storage, CRUD, sort/filter.
* **`UIManager`:** DOM, rendering, modals, UI feedback.
* **`AppCore`:** Orchestrates modules and events.

## Future Ideas

* Drag & drop reorder, advanced filters, themes, backend sync, reminders, undo.
