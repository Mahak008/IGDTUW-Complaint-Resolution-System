# IGDTUW-Complaint-Resolution-System

## Description

This project is a web application developed with Spring Boot, utilizing HTML, CSS, and Bootstrap for the frontend. It employs MongoDB as the database for storing data and Maven for dependency management.

## Features

- User authentication and authorization
- CRUD operations with MongoDB
- Responsive design using Bootstrap
- API endpoints

## Technologies Used

- **Spring Boot**: Framework for creating the backend and managing application configuration.
- **HTML/CSS**: For structuring and styling the web pages.
- **Bootstrap**: For responsive and modern design components.
- **MongoDB**: NoSQL database for data storage.
- **Maven**: Build automation and dependency management.
- **Eclipse IDE**: Integrated development environment used for development.

## Getting Started

### Prerequisites

Ensure you have the following installed:

- Java Development Kit (JDK) 8 or higher
- Maven
- MongoDB Compass
- Eclipse IDE

### Clone the Repository

```bash
git clone https://github.com/yourusername/your-repository-name.git
cd your-repository-name
```

### Update the application.properties file in the src/main/resources directory with your MongoDB connection details. For Example:
```bash
spring.data.mongodb.uri=mongodb://localhost:27017/your-database-name
```

## Folder Structure
- src/main/java: Java source code
- src/main/resources: Configuration files and static resources (e.g., application.properties)
- src/main/resources/static: Static files like CSS, JavaScript, and images
- src/main/resources/templates: Thymeleaf templates for rendering HTML
- src/test/java: Unit and integration tests
- pom.xml: Maven build file

## Contributing

If you want to contribute to this project, please follow these steps:

1. **Fork the repository**: Click the "Fork" button at the top right of the repository page to create your own copy.
2. **Create a new branch**: Switch to a new branch for your changes.
    ```bash
    git checkout -b feature-branch
    ```
3. **Commit your changes**: Add your changes and commit them with a meaningful message.
    ```bash
    git commit -am 'Add new feature'
    ```
4. **Push to the branch**: Push your changes to your forked repository.
    ```bash
    git push origin feature-branch
    ```
5. **Create a new Pull Request**: Navigate to the original repository and click on "New Pull Request". Provide a description of your changes and submit the pull request for review.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements

- [Spring Boot](https://spring.io/projects/spring-boot) for providing the framework
- [Bootstrap](https://getbootstrap.com) for the front-end framework and styling components
- [MongoDB](https://www.mongodb.com) for the database management
- [Eclipse IDE](https://www.eclipse.org) for the development environment
