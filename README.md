# Kanban Board App

## Overview



This project is a Kanban board application built using ReactJS. It allows users to interact with ticket data fetched from the [Quicksell API](https://api.quicksell.co/v1/internal/frontend-assignment). Users can group and sort tickets based on different criteria, making it a versatile tool for project management.See live on https://quickseell-assignment.vercel.app/.


## Features

- **Data Interaction:**

  - Fetches ticket data from the Quicksell API.
  - Displays the fetched data on a Kanban board.

- **Grouping Options:**

  - Group tickets by Status, User, or Priority.

- **Sorting Options:**

  - Sort tickets by Priority or Title.

- **Priority Levels:**

  - Tickets are categorized with priority levels ranging from Urgent (4) to No Priority (0).

- **Styling:**

  - Visually appealing and responsive design.
  - Pure CSS is used for styling.

- **Icons:**

  - Icons are integrated for various elements of the application using react-icon.

- **State Persistence:**
  - Saves the user's view state (grouping and sorting options) even after a page reload using local storage.

## Setup

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/manushukla2/Quickseell_Assignment.git
   ```

2. **Navigate to the Project Directory:**

   ```bash
   cd kanban-board-app
   ```

3. **Install Dependencies:**

   ```bash
   npm install
   ```

4. **Run the Application:**

   ```bash
   npm start
   ```

5. **Access the Application:**
   Open your browser and go to `http://localhost:3000`.



## Live Demo

You can view the live demo of this project 
https://quickseell-assignment.vercel.app/


## Usage

- 1.*Click the "Display" button to fetch and display the tickets from the provided API.*
- 2.*Select one of the three grouping options: "By Status," "By User," or "By Priority."*
- 3.*Choose the sorting option: "Priority" or "Title."*
- 4. *The Kanban board will dynamically adjust to reflect your choices.*

## Contributing
If you'd like to contribute to this project, please follow these guidelines:

-1.*Fork the repository on GitHub.*
-2.*Clone the forked repository to your local machine.*
-3.*Create a new branch for your feature or bug fix:*
```bash

git checkout -b feature/your-feature-name
```
-4.*Make your changes, commit them, and push to your fork.*
-5.*Open a pull request to the original repository, explaining the changes you made.*   

## Contact
If you have any questions, suggestions, or feedback, feel free to contact the project maintainer:

Name: Manu Shukla
Email: manushukla0210@gmail.com

Enjoy using the Kanban board application to manage your tasks efficiently!
