# Expense Tracker File Structure

## File Structure
│
├── Home.html
├── AddNewExpence.html
├── ExpenceList.html
├── UpdateExpense.html
├── Login.html
├── Registration.html
├── Login.css
└── README.md

## Overview

This project is a simple web-based Expense Tracker application that allows users to:

- Register and log in to the application
- Add new expenses
- View a list of recorded expenses
- Update existing expenses

The project uses local storage in the browser to save and retrieve data. No back-end server or database is involved.

## Technologies Used

- **HTML5**: For the structure of the web pages.
- **CSS3**: For styling the layout and components.
- **JavaScript**: For adding interactivity and saving/retrieving data from local storage.
- **Local Storage**: Browser-based storage to persist user data like expenses.

## Pages

### 1. Home Page (`Home.html`)
The landing page that provides navigation to:
- Add new expenses
- View the list of expenses

### 2. Add New Expense (`AddNewExpence.html`)
A form where users can input new expense details, including:
- Expense Name
- Amount
- Date
- Description

On form submission, the expense details are stored in the browser's local storage, and the user is redirected to the Expense List page.

### 3. Expense List (`ExpenceList.html`)
This page displays a list of all expenses stored in local storage. Each expense shows:
- Expense Name
- Amount
- Date
- Description

It also provides an option to update the existing expenses by redirecting users to the "Update Expense" page.

### 4. Update Expense (`UpdateExpense.html`)
Allows users to modify the details of an existing expense. The updated data is saved to local storage, replacing the old information.

### 5. Login (`Login.html`)
A login form for users to authenticate. On successful login (currently no authentication logic), the user is redirected to the home page.

### 6. Registration (`Registration.html`)
A registration form where users can create an account. Currently, no backend logic is connected, so form data is not persisted.


### Key Points:
- The project is simple, without any backend integration.
- Local storage is used to store expenses.
- Each page's functionality is explained in the **Pages** section.

You can adjust this as necessary to fit your exact setup and add any other details that you might find relevant!
