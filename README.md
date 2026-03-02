# Student Management System

A simple **Flask-based Student Management System** that allows users to register, log in, view, and edit student details.  
This project demonstrates the use of **HTML templates, CSS styling, and Flask routes** to build a basic CRUD (Create, Read, Update, Delete) web application with authentication.

---

## 🚀 Features

- **User Authentication**
  - `register.html` → User registration form
  - `login.html` → User login form with validation

- **Student Management**
  - `index.html` → Student registration form
  - `view.html` → View all registered students
  - `edit.html` → Edit existing student details

- **Styling**
  - Custom CSS (`static/style.css`) for forms, tables, and buttons
  - Gradient headings, hover effects, and clean layout

---

## 📂 Project Structure


# Student Management System - Stylesheet

This repository contains a custom CSS stylesheet used to style the **Student Management System** project.  
The stylesheet defines the layout, colors, and formatting for forms, tables, and buttons.

## 🎨 Features

- **Global Styling**
  - Sets font family to *Arial, sans-serif*
  - Applies a red background color to the page

- **Headings**
  - Custom gradient color applied to `<h1>` elements

- **Forms**
  - White background with padding and rounded corners
  - Styled input fields with full width
  - Blue submit button with hover effect

- **Tables**
  - Collapsed borders for clean look
  - White background with green-bordered cells
  - Light gray header row

## 🛠️ Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/ABC123cijdicjjej/student-management-system.git
# Student Management System - Edit Student Template

This repository contains the **Edit Student** HTML template used in the Student Management System project.  
The template provides a form for editing student details such as **Name, Age, and Course**.

---

## 🖼️ File Overview

**File:** `templates/edit.html`  
**Purpose:** Allows users to update student information stored in the system.

### Code Snippet
```html
<!DOCTYPE html>
<html>
<body>
    <h2><b>Edit Student</b></h2>
    <form method="POST">
        <label>Name</label><br>
        <input type="text" name="name" value="{{ student[0]}}"><br>
        <label>Age</label><br>
        <input type="text" name="age" value="{{ student[1]}}"><br>
        <label>Course</label><br>
        <input type="text" name="course" value="{{ student[2]}}"><br>
        <button type="submit">Update</button>
    </form>
    <br>
    <a href="/view">Back</a>
</body>
</html>
-----------------------------------------------------
