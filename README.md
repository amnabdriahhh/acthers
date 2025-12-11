# Acthers Library System

## Project Description
Acthers Library System is a web-based library management interface designed for easy management of books, members, and borrowing activities. The system allows users to register, log in, view the library dashboard, explore available books, and see registered members. It provides a visually appealing interface with charts for borrowing trends and an organized overview of library resources.

---

## Features Included
- **User Authentication**
  - User registration with validation for empty fields and email format.
  - User login with verification of username and password.
- **Dashboard**
  - Overview cards for total books, members, borrowed books, top genres, most active member, and overdue books.
  - Charts displaying monthly borrowed books, genre distribution, and borrowing durations.
- **Books Management**
  - View a list of available books with images, title, author, genre, and status (available/borrowed).
  - Filter books by genre.
  - Request a new book with a submission form.
- **Members**
  - Display all registered library members in a structured layout with contact information.
- **Responsive Design**
  - Mobile-friendly navigation bar and layout.

---

## Instructions to Test Login
1. Open the project folder in a browser.
2. Navigate to `register.html` to create a new account.
   - Fill in all required fields (Full Name, Email, Username, Password).
   - Ensure the email contains an `@` symbol.
   - Click **Register**.
3. Upon successful registration, you will be redirected to `index.html`.
4. On the login page (`index.html`):
   - Enter the registered **Username** and **Password**.
   - Click **Login**.
5. If credentials are correct, you will be redirected to `dashboard.html`.
6. Incorrect login attempts or missing fields will display error messages.

---

## Frameworks / Libraries Used
- **Bootstrap 5.3.8** – For responsive layout and styling.
- **Chart.js 3.5.1** – For displaying bar, line, and doughnut charts in the dashboard.
- **LocalStorage** – To store user registration data and simulate login functionality.

