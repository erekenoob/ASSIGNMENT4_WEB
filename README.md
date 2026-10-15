# ASSIGNMENT4_WEB
# Assignment #4: Forms and Validation

## Project Overview
This project was created as part of **Assignment 4 Forms and Validation**. The objective is to demonstrate how to build user-friendly web forms using native HTML5 and style them using **Bootstrap 5** components, grids, and validation classes.


## Project Structure & Tasks

The website is connected via a responsive **Navbar** across 4 separate pages:

1 **`index.html` Home Page**
   - Contains student information and the main navigation bar to switch between different tasks.

2 **`task1.html` Part 1: Basic HTML Forms — Task 0 & Task 1**
   - A clean, basic contact form built with standard HTML tags (`<form>`, `<label>`, `<input>`, `<textarea>`, `<button>`).
   - Implements built-in **HTML5 validation** attributes: `required`, `type="email"`, `minlength`, and `maxlength`.

3 **`task2.html` Part 2: Bootstrap Forms — Task 2 & Task 3**
   - Recreates the contact form using Bootstrap 5 classes (`.form-label`, `.form-control`, `.form-text`, `.btn`).
   - Demonstrates Bootstrap's validation styles using `.is-valid` and `.is-invalid` classes alongside `.valid-feedback` and `.invalid-feedback` messages.

4 **`task4.html` Part 3: Advanced Form Project — Task 4**
    A full **User Registration Form** arranged responsively using the **Bootstrap Grid System** (`.row`, `.col-md-6`).
   - Includes diverse form controls:
   - First Name & Last Name Text inputs
   - Email Address `type="email"`
   - Password & Confirm Password `type="password"`, `minlength="8"`
   - Gender **Radio buttons** `.form-check-input`
   - Hobbies **Checkboxes** `.form-check-input`
   - Country **Select dropdown** `.form-select`
   - Submit and Reset **buttons**
   - Uses Bootstrap's `.was-validated` class on the `<form>` element to provide real-time CSS-based validation feedback alongside HTML5 attributes.



## Technologies Used
- **HTML** (Semantic form elements & built-in validation)
- **CSS** (Basic layout styling for Task 1)
- **Bootstrap** (Grid system, Navbar, Form controls, and Validation styles via CDN)
