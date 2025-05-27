# Coding Challenge: NestJS Backend with Employee Module and Email Service

Welcome to your coding challenge! 👋

Your task is to set up a NestJS backend, focusing on building an employee management module with CRUD functionalities, integrated with an email service that operates through a queue system.

## 🎯 Assignment

**Objective:** Develop a NestJS backend application with an employee module for managing employee data and an email service triggered by a queue.

### Key Features:

1. **Employee Module:**

   - **Create Employee Endpoint:** Add new employees with basic details like name, job title, and department.
   - **Read Employee Endpoint:** Retrieve employee details using their ID and list all employees.
   - [optional] **Update Employee Endpoint:** Update an employee's job title and department.
   - [optional] **Delete Employee Endpoint:** Remove an employee from the system.

2. **Simple Email Service:**

   - Integrate an email service that sends notifications (e.g., welcome email on employee creation).
   - Use a queue system (like Bull) to manage and trigger email notifications asynchronously.

3. **Basic Setup and Configurations:**

   - Feel free to use a NestJS boilerplate for initial setup.
   - Set up basic validation for input data and error handling for the CRUD operations.
   - Implement a simple data storage solution (in-memory or a basic database setup).
   - We're using a GraphQL API using Apollo Server, but feel free to decide for yourself if you want to go for a REST or GraphQL based API.

4. **Documentation:**
   - Provide comments and basic documentation for understanding the implemented features.

### 📋 Deliverables:

- Source code for the NestJS application, including the employee module and email service.
- Instructions on how to set up and run the application.
- Feel free to submit your result as a private repo and make sure to invite the following collaborators: ales@project-b.dev, samim@project-b.dev, felix@project-b.dev, dmitry@project-b.dev.

### 🗣️ Discussion Points for Review:

- Design decisions and rationale behind them.
- Challenges faced and how they were addressed.
- Considerations for scaling and maintaining the application.

_*We're looking forward to seeing your approach to building this solution. Happy coding!*_
