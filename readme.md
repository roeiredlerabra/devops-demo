# Work Item Manager

This repository contains a project that implements a login page for user authentication and a work item management system. The project retrieves work item data from an API and provides a user-friendly interface to view and interact with the items.

## 📚 Documentation

### 🚪 Login Page

The login page features a form where users can enter their username and password. Upon submission, the entered credentials are validated through an API call. If the credentials are valid, the login page is hidden, and the work items page is displayed.

### 📋 Work Items Page

The work items page showcases a DataTable component that presents a list of work items fetched from an API. Each row in the table represents a specific work item. Clicking on a row opens a modal that displays detailed information about the selected work item.

### 💻 Technologies

The following technologies were used in this project:

- HTML and CSS: Used for layout and styling of the pages.
- jQuery: Employed for DOM manipulation and event handling.
- Bootstrap: Utilized for creating a responsive design and implementing the modal functionality.
- DataTables: Integrated to enable advanced features for the table, such as sorting and pagination.
- Fetch API: Utilized for asynchronous retrieval of data from the API.

### 🔑 Key Functions

The project includes several key functions:

- `validateUser()`: Handles the submission of the login form and performs the API call to validate the user's credentials.
- `fetchData()`: Retrieves work item data from the API.
- `updateTable()`: Dynamically populates the DataTable with the fetched work items.
- `showModal()`: Displays the details of a selected work item in a modal.

### 🧠 Logic Flow

The logic flow of the project follows these steps:

1. User submits the login form.
2. The submitted credentials are validated through an API call.
3. If the validation is successful, the work items page is displayed.
4. The table on the work items page is populated by calling the `updateTable()` function.
5. Clicking on a row in the table opens a modal, showing the details of the selected work item.
6. The code is structured to ensure separation of concerns and maintain logical units.

### 🎯 Purpose

The main objectives of this project are:

- Authenticate and authorize users to ensure secure access.
- Retrieve and update work item data dynamically from the API.
- Enable user interactions beyond static lists.
- Support large datasets through pagination.
- Design modular and reusable code for maintainability.
- Load data asynchronously to avoid blocking the user interface.
- Implement a responsive design that adapts to different devices.
- Handle errors gracefully to provide a smooth user experience.

## 🏃‍♀️ Running the Project

TODO: Instructions for running and testing the project will be added here.

## 🤝 Contributing

TODO: Guidelines for contributing to the project will be added here.

This README file provides an overview of the project, including explanations of the code's logic, purposes, and technologies used. If you require further clarification on any aspect, please let me know!
