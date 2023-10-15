# Envision: Collaborative Management Platform
The Management Platform For Dynamic Teams

![Envision Logo](./envision-logo.png)

## Table of Contents

- [Introduction](#introduction)
- [Key Features](#key-features)
- [Project Structure](#project-structure)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
  - [Task Management](#task-management)
  - [Project Collaboration](#project-collaboration)
  - [Real-Time Collaboration](#real-time-collaboration)
  - [File Storage](#file-storage)
  - [Integration](#integration)
  - [Mobile Compatibility](#mobile-compatibility)
- [Technologies Used](#technologies-used)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Welcome to Envision, a powerful and comprehensive collaborative management platform designed to help individuals, teams, and organizations efficiently plan, collaborate, and manage their projects, tasks, and meetings. Envision is your one-stop solution for boosting productivity and fostering seamless teamwork, all within a unified platform.

![Envision Screenshot](./envision-screenshot.png)

## Key Features

Envision offers a rich array of features to streamline your management processes and enhance your productivity:

### Task Management

- Create tasks, set priorities, and track progress efficiently.
- Assign tasks to team members or contributors.
- Set due dates and reminders to stay organized.
- Categorize tasks into projects or categories.

### Project Collaboration

- Create projects and invite team members to collaborate.
- Share project details, files, and task lists.
- Collaborate in real time on project documents.
- Discuss project-related matters in a built-in chat system.

### Real-Time Collaboration

- Collaborate on documents and spreadsheets in real time.
- Edit and comment on documents simultaneously.
- Receive real-time notifications for document changes and comments.
- Foster a productive and interactive work environment.

### File Storage

- Securely store and access files, including PDFs, images, and documents.
- Organize files into folders or categories for easy retrieval.
- Share files with team members and external stakeholders.
- Keep your digital assets organized and accessible.

### Integration

- Seamlessly integrate with popular services:
  - Google Forms: Create and collect data via forms.
  - Google Sheets: Export and sync data with Google Sheets.
  - GitHub: Incorporate version control into your projects.
  - Google Meet: Schedule, join, and manage video meetings.

### Mobile Compatibility

- Access Envision on both web and mobile platforms:
  - Web Application: Access Envision via browsers on desktop and mobile devices.
  - Mobile Application: Download the Envision mobile app (available for iOS and Android) for on-the-go access.

## Project Structure

Envision adheres to a microservices architecture, offering scalability and modularity:

- `client/`:
  - `web/`: Web application (React)
  - `mobile/`: Mobile application (React Native)
- `server/`: Back-end microservices
- `shared/`: Shared code and resources
- `docker-compose.yml`: Docker container orchestration
- `.env`: Environment variables
- `.gitignore`: Git ignore rules
- `README.md`: This documentation

## Getting Started

### Prerequisites

Before getting started, ensure you have the following prerequisites installed:

- Node.js and npm
- Docker (for containerization)
- Docker Compose (for orchestration)

### Installation

1. Clone the repository:
   ```
   git clone https://github.com/yourusername/envision.git
   cd envision
   ```

2. Set up environment variables:
   - Create a `.env` file based on `.env.example` and populate it with the necessary environment variables.

3. Start the services:
   ```
   docker-compose up
   ```

4. Access the web application at `http://localhost:3000` and the mobile application as needed.

## Usage

Envision can be used for various purposes, making it a versatile platform:

### Task Management

Organize your daily tasks, set priorities, and track your progress. Collaborate on task lists and assign tasks to team members.

### Project Collaboration

Create projects, assign tasks, and collaborate with team members. Share project details, files, and task lists for streamlined teamwork.

### Real-Time Collaboration

Collaborate in real time on documents, spreadsheets, and projects. Edit and comment on documents simultaneously and receive real-time notifications for document changes and comments.

### File Storage

Securely store and manage files, including PDFs, images, and documents. Organize files into folders or categories and share them with team members and external stakeholders.

### Integration

Seamlessly integrate with popular services to enhance your workflow:

- Google Forms: Create and collect data via custom forms.
- Google Sheets: Export and sync data with Google Sheets.
- GitHub: Implement version control and collaborative project management.
- Google Meet: Schedule, join, and manage video meetings within your projects.

### Mobile Compatibility

Access Envision on both web and mobile platforms:

- Web Application: Access Envision via browsers on desktop and mobile devices.
- Mobile Application: Download the Envision mobile app (available for iOS and Android) for on-the-go access.

## Technologies Used

Envision is built using a robust technology stack, including:

- Front-End:
  - React
  - React Native
  - Redux
  - Material-UI (web)
  - React Native Components (mobile)

- Back-End:
  - Node.js
  - Express.js
  - MongoDB (user and project data)
  - MySQL/PostgreSQL (authentication)
  - Docker
  - WebSocket (real-time collaboration)
  
- Integration and APIs:
  - Google APIs (Forms, Sheets, Drive, and Meet)
  - GitHub API
  - OAuth 2.0

## Contributing

Contributions to Envision are welcome! To contribute, please follow these steps:

1. Fork the project.
2. Create a new branch for your feature or bug fix.
3. Make your changes.
4. Test your changes.
5. Submit a pull request.

Please ensure that your code follows our coding guidelines and is well-documented.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

Feel free to customize this README to include even more specific information about your Envision project, its features, and setup instructions. This comprehensive documentation serves as a guide for users and contributors, showcasing the capabilities and potential of your collaborative management platform.
