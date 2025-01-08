# User File Upload Application

A full-stack application that allows users to upload files securely to Amazon S3, built with Java, Spring Boot, and React.js. The application integrates PostgreSQL with Docker for consistent local development and data management.

## Features
- **Secure file uploads**: Users can upload files to Amazon S3 securely.
- **PostgreSQL database**: Configured with Docker for consistent data management across environments.
- **AWS S3 integration**: Optimized for secure file handling and efficient uploads.

## Technologies
- **Frontend**: React.js
- **Backend**: Java, Spring Boot
- **Database**: PostgreSQL (Docker)
- **File Storage**: Amazon S3
- **Containerization**: Docker

## Installation
1. Clone the repository:
    ```bash
    git clone https://github.com/sofiaJYX/User-File-Upload-Application.git
    ```
2. Set up Docker for PostgreSQL:
    ```bash
    docker-compose up
    ```
3. Configure your AWS S3 credentials in the application settings.
4. Install dependencies for the backend:
    ```bash
    mvn install
    ```
5. Install dependencies for the frontend:
    ```bash
    npm install
    ```
6. Start the backend server:
    ```bash
    mvn spring-boot:run
    ```
7. Start the frontend development server:
    ```bash
    npm start
    ```

## Deployment
The backend is deployed with **Spring Boot**, integrating securely with **AWS S3** for file handling. **PostgreSQL** is configured with Docker for local development, ensuring consistency across environments.

## License
MIT License.
