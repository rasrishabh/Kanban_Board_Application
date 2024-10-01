# Kanban Board Application

This Kanban board application is built using **React JS** and leverages the API provided by [QuickSell](https://api.quicksell.co/v1/internal/frontend-assignment) to dynamically manage and organize tasks. Users can group and sort tasks based on their preferences, providing flexibility and efficiency in task management. The application also preserves the user's customized view even after a page reload.

## Key Features

- **Dynamic Grouping**: Organize tickets by status, user, or priority.
- **Advanced Sorting**: Sort tickets by priority or title for better task prioritization.
- **Persistent View State**: Your selected grouping and sorting options are saved in local storage, ensuring your preferences are retained.
- **Priority Levels**: Tasks are assigned a priority value:
  - **Urgent** (4)
  - **High** (3)
  - **Medium** (2)
  - **Low** (1)
  - **No Priority** (0)
- **Responsive UI**: Designed to be visually appealing and adaptable to various screen sizes, offering an optimal user experience.

## Live Demo

Explore the live version of the Kanban board application [here]().

## Getting Started

To run the Kanban board application locally, follow the steps below:

### Prerequisites
- Ensure **Node.js** and **npm** are installed on your machine.

### Installation Steps

1. **Clone the Repository**:
    ```bash
    git clone https://github.com/rasrishabh/Kanban_Board_Application.git
    ```

2. **Navigate to the Project Directory**:
    ```bash
    cd kanban-board
    ```

3. **Install Dependencies**:
    ```bash
    npm install
    ```

4. **Start the Development Server**:
    ```bash
    npm start
    ```

5. **Access the Application**:  
   Open your web browser and go to `http://localhost:3000` to use the application.

## Usage Instructions

1. **Display Tickets**: Click the "Display" button to fetch and show the tickets from the API.
2. **Group Tickets**: Select one of the grouping options - by Status, User, or Priority.
3. **Sort Tickets**: Choose to sort by Priority or Title to arrange the tasks as needed.
4. **Persistent Preferences**: Your view settings will be saved automatically, ensuring they are retained after a page reload.

## Contribution Guidelines

Contributions to enhance this project are welcome! To contribute:

1. **Fork the Repository**: Create your own copy of the project.
2. **Create a Branch**: Create a new branch for your feature or bug fix.
    ```bash
    git checkout -b feature/your-feature-name
    ```
3. **Make Changes**: Implement your feature or fix.
4. **Push Your Changes**:
    ```bash
    git push origin feature/your-feature-name
    ```
5. **Submit a Pull Request**: Once your changes are ready, open a pull request, detailing the updates you’ve made.

## Contact Information

For questions, suggestions, or feedback, feel free to reach out to the project maintainer:

- **Name**: Rishabh Soni
- **Email**: [rishabh.soni.met21@itbhu.ac.in](mailto:rishabh.soni.met21@itbhu.ac.in)
