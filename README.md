# Mentor-Mentee Dashboard

Welcome to the **Mentor-Mentee Dashboard**! This platform serves as a streamlined solution for mentors to monitor their mentees' progress and engagement while allowing mentees to submit their personal and academic details, raise queries, and maintain communication with their mentors.

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
  - [Running the Application](#running-the-application)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)

## Overview

The **Mentor-Mentee Dashboard** is designed to simplify the mentor-mentee relationship by providing an easy-to-use interface for submitting details, tracking academic progress, and raising queries. Mentors can efficiently manage and guide their mentees through the dashboard, while mentees can stay organized and connected.

## Features

- **Mentee Profile Management:** Mentees can fill out personal, academic, and miscellaneous details through structured forms.
- **Mentor View:** Mentors can view submitted forms, manage queries, and track mentee progress.
- **Query Submission:** Mentees can raise queries for their mentors to respond to directly via the dashboard.
- **Dynamic Form Fields:** Form fields dynamically adjust based on user input (e.g., number of siblings, family income).
- **Role-Specific Dashboards:** Separate dashboards for mentors and mentees, with unique functionalities for each role.
- **Accessibility Options:** Improved accessibility for all users through customizable settings.

## Technologies Used

- **Frontend:** React.js
- **Backend:** Node.js, Express.js
- **Database:** PostgreSQL, MongoDB (optional for NoSQL functionality)
- **Version Control:** Git, GitHub
- **UI Components:** HTML, CSS

## Getting Started

Follow these instructions to set up and run the project locally.

### Prerequisites

- **Node.js** installed on your machine.
- **Git** installed for version control.
- **PostgreSQL** or **MongoDB** for the database.

### Installation

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/Abaan9350/mentee_dash.git
   ```

2. **Navigate to the Project Directory:**

   ```bash
   cd mentee_dash
   ```

3. **Install Dependencies:**

   ```bash
   npm install
   ```

### Running the Application

1. **Start the Backend Server:**

   ```bash
   npm start
   ```

2. **Run the Frontend:**

   Use a separate terminal for this:

   ```bash
   npm run client
   ```

   The application will now be accessible at `http://localhost:3000`.

## Project Structure

```bash
mentee_dash/
├── client/           # React frontend code
├── server/           # Express backend code
├── public/           # Static assets
├── node_modules/     # Node.js dependencies
├── package.json      # Project dependencies and scripts
└── README.md         # Project documentation
```

## Contributing

We welcome contributions! To contribute:

1. Fork the repository.
2. Create a new branch for your feature or bugfix.
3. Commit your changes.
4. Push the branch and create a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more information.
