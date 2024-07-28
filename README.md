# Neural-Ninjas


# ProgressPal

The ProgressPal is a web application designed to streamline team task management. Built using the MERN stack (MongoDB, Express.js, React, and Node.js), this platform provides a user-friendly interface for efficient task assignment, tracking, and collaboration. The application caters to administrators and regular users, offering comprehensive features to enhance productivity and organization.

## Table of Contents

- [Background](#background)
- [Features](#features)
  - [Admin Features](#admin-features)
  - [User Features](#user-features)
  - [General Features](#general-features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Background

With the rise of remote work and dispersed teams, there is a growing need for tools that facilitate effective communication and task coordination. The ProgressPal addresses this need by leveraging modern web technologies to create an intuitive and responsive task management solution. The MERN stack ensures scalability, while the integration of Redux Toolkit, Headless UI, and Tailwind CSS enhances user experience and performance.

## Features

### Admin Features

#### User Management
- Create admin accounts.
- Add and manage team members.

#### Task Assignment
- Assign tasks to individual or multiple users.
- Update task details and status.

#### Task Properties
- Label tasks as to-do, in-progress, or completed.
- Assign priority levels (high, medium, normal, low).
- Add and manage sub-tasks.

#### Asset Management
- Upload task assets, such as images.

#### User Account Control
- Disable or activate user accounts.
- Permanently delete or trash tasks.

### User Features

#### Task Interaction
- Change task status (in-progress or completed).
- View detailed task information.

#### Communication
- Add comments or chat to task activities.

### General Features

#### Authentication and Authorization
- User login with secure authentication.
- Role-based access control.

#### Profile Management
- Update user profiles.

#### Password Management
- Change passwords securely.

#### Dashboard
- Provide a summary of user activities.
- Filter tasks into to-do, in-progress, or completed.

## Technologies Used

### Frontend
- React (Vite)
- Redux Toolkit for State Management
- Headless UI
- Tailwind CSS

### Backend
- Node.js with Express.js

### Database
- MongoDB for efficient and scalable data storage.

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/jayg2309/Neural-Ninjas.git
    cd Neural-Ninjas
    ```

2. Install dependencies for the backend:
    ```bash
    cd backend
    npm install
    ```

3. Install dependencies for the frontend:
    ```bash
    cd ../frontend
    npm install
    ```

## Usage

1. Start the backend server:
    ```bash
    cd backend
    npm start
    ```

2. Start the frontend server:
    ```bash
    cd ../frontend
    npm run dev
    ```

3. Open your browser and navigate to `http://localhost:3000` to use the application.



## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

