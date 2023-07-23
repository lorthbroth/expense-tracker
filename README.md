# Expense Tracker

Expense Tracker is a web-based application that helps users manage their expenses effectively. The application provides a user-friendly interface to log, categorize, and track expenses over time. It enables users to monitor their spending habits, set budgets, and make informed financial decisions.

## Key Features

- User Registration and Authentication: Users can sign up for the application with a valid email and password. Upon successful registration, users will be able to log in to their accounts using JWT authentication.

- Expense Logging: Authenticated users can log their expenses by providing details such as the expense amount, date, category (e.g., groceries, utilities, entertainment), and optional description.

- Expense Categories: Users can categorize their expenses into predefined categories or create custom categories to better organize their spending.

- Expense Visualization: The application will display visualizations like charts and graphs to help users understand their spending patterns over time. This can include pie charts showing the distribution of expenses across different categories and line charts showing monthly expenditure trends.

- Budget Setting and Tracking: Users can set monthly or custom budgets for different expense categories. The application will track actual spending against these budgets and provide users with notifications or alerts if they are close to or exceeding their set limits.

- Data Analytics: Users can generate expense reports for specific time periods, categories, or custom filters. This feature enables users to analyze their spending in detail and make data-driven decisions.

- Responsive Design: The frontend application will be developed using Angular with a responsive design to ensure a seamless user experience on various devices, including desktops, tablets, and mobile phones.

## Tech Stack

### Backend

- Quarkus: Java framework for building the backend with excellent performance and efficient memory utilization, suitable for reactive applications.
- SmallRye Mutiny: Used for handling asynchronous and reactive programming, beneficial for handling streams of data.
- JSON-B: For efficient serialization and deserialization of JSON data in the backend.
- JWT Authentication: To secure the backend APIs and authenticate users during login and other sensitive operations.
- MongoDB: NoSQL database to store expense records and user information.

### Frontend

- Angular: The frontend will be developed using Angular, a popular TypeScript-based web application framework, providing a structured and dynamic user interface.
- Angular Material: To leverage pre-built UI components and design patterns for a consistent and attractive user interface.
- Chart.js or D3.js: For creating interactive and visually appealing charts and graphs to display expense data and statistics.

## Implementation Considerations

- Ensure that the application has proper error handling and validation to handle user input and prevent common security vulnerabilities like SQL injection or Cross-Site Scripting (XSS).
- Implement role-based access control (RBAC) to restrict certain actions or views to specific user roles, e.g., admin, regular user.
- Utilize Reactive Programming principles throughout the application to handle asynchronous operations efficiently and enhance responsiveness.
- Implement proper data sanitization and validation to prevent incorrect or malicious data from being stored in the database.

## Getting Started

Follow the instructions below to set up and run the Expense Tracker application locally.

### Prerequisites

- Node.js: Make sure you have Node.js installed on your system. You can download it from the official website (https://nodejs.org/).

### Backend Setup

1. Clone this repository to your local machine.
2. Navigate to the `backend` directory.
3. Run `mvn clean install` to build the backend application.
4. Start the backend server by running `mvn quarkus:dev`.

### Frontend Setup

1. Navigate to the `frontend` directory.
2. Run `npm install` to install the required dependencies.
3. Start the frontend development server by running `ng serve`.

The application will now be accessible at http://localhost:4200 in your web browser.

## License

This project is licensed under the [MIT License](LICENSE).

## Contributing

Contributions are welcome! If you'd like to contribute to this project, please fork the repository and submit a pull request.
