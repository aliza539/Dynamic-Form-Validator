# Dynamic-Form-Validator SPA 
## Overview

**Dynamic Form Validator** is a Single Page Application (SPA) built using **pure JavaScript and the DOM API**. The project demonstrates how modern frontend applications can be created without frameworks by directly manipulating the DOM, handling events efficiently, and managing application state in the browser.

The application allows users to create, edit, and delete tasks through a dynamic interface while validating form inputs in real time. It uses **debouncing for input validation**, **throttling for window resize performance**, and **event delegation** to efficiently handle actions on dynamically created elements.

The project also persists application state using **localStorage**, ensuring that tasks remain available even after the page is refreshed.

## Key Features

### Dynamic Task Management

* Add new tasks through a form
* Edit existing tasks
* Delete tasks instantly
* Dynamic DOM updates without page reload

### Live Form Validation

* Real-time validation for task input and email fields
* Debounced validation to prevent excessive event processing
* Invalid inputs are visually highlighted

### Event Delegation

* A single event listener manages actions for dynamically created elements
* Efficient handling of **edit** and **delete** operations on the task list

### Performance Optimization

* **Debouncing** prevents unnecessary validation executions during typing
* **Throttling** limits expensive operations triggered by window resize events

### DOM Manipulation

The project demonstrates multiple DOM operations including:

* Selecting elements
* Traversing DOM nodes
* Creating and inserting elements
* Updating content dynamically
* Removing elements

### Persistent Storage

* Tasks are stored in **localStorage**
* Data is saved using **JSON serialization**
* Tasks automatically reload when the page is refreshed

---

## Technologies Used

* **HTML5** – application structure
* **CSS3** – basic layout and styling
* **JavaScript (ES Modules)** – application logic
* **DOM API** – dynamic UI manipulation
* **localStorage** – client-side persistence

---

## Core JavaScript Concepts Demonstrated

This project focuses on important frontend engineering concepts:

* DOM tree manipulation
* Event handling with `addEventListener`
* Event propagation and **event delegation**
* Debouncing using `setTimeout`
* Throttling using time-based execution control
* Form submission handling with `preventDefault`
* State persistence using `localStorage` and `JSON`

---

## How It Works

1. The user submits a task through the form.
2. Form submission is intercepted using `preventDefault`.
3. Input values are validated before creating a task.
4. A new task element is dynamically generated and added to the DOM.
5. The task is stored in `localStorage`.
6. Event delegation listens for edit or delete actions on the task list.
7. Debounced validation ensures input checks occur only after typing pauses.
8. Throttling ensures resize-related logic runs at controlled intervals.

---

## Learning Objectives

This project is designed to strengthen understanding of:

* Core JavaScript without frameworks
* DOM manipulation patterns
* Efficient event management
* Frontend performance optimization
* Building maintainable modular JavaScript applications

---

## Running the Project

Simply open the `index.html` file in a browser.

No additional dependencies or build tools are required.
