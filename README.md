# JournalApp

A simple Java-based journaling application that helps users record and organize their daily thoughts and experiences.

## Project Structure

```
journalApp/
├── .idea/               # IntelliJ IDEA configuration files
├── .mvn/                # Maven wrapper directory
├── src/                 # Source code
│   ├── main/            # Application source code
│   │   ├── java/        # Java source files
│   │   │   └── net/engineeringdigest/journalApp/
│   │   │       └── JournalApplication.java  # Main application class
│   │   └── resources/   # Application resources
│   │       ├── static/  # Static files (CSS, JS, images)
│   │       └── templates/ # HTML templates
│   └── test/            # Test code
├── target/              # Compiled output (generated)
├── .gitignore           # Git ignore file
├── HELP.md              # Helper documentation
├── mvnw                 # Maven wrapper script (Unix)
├── mvnw.cmd             # Maven wrapper script (Windows)
└── pom.xml              # Maven project configuration
```

## Features

- Create and manage journal entries
- Organize entries by date, tags, or categories
- Search functionality to find specific entries
- Simple and intuitive user interface
- Secure storage of personal journal entries

## Technologies Used

- Java
- Spring Boot
- Maven for dependency management
- Thymeleaf for templating
- Bootstrap for responsive design

## Getting Started

### Prerequisites

- Java JDK 11 or higher
- Maven (or use the included Maven wrapper)

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/journalApp.git
   cd journalApp
   ```

2. Build the project:
   ```bash
   ./mvnw clean install
   ```
   or on Windows:
   ```bash
   mvnw.cmd clean install
   ```

3. Run the application:
   ```bash
   ./mvnw spring-boot:run
   ```
   or on Windows:
   ```bash
   mvnw.cmd spring-boot:run
   ```

4. Open your browser and navigate to:
   ```
   http://localhost:8080
   ```

## Usage

1. Create a new account or log in
2. Create a new journal entry by clicking the "New Entry" button
3. Fill in the date, title, and content for your entry
4. Add tags if desired
5. Save your entry
6. View past entries in the calendar or list view

## Configuration

The application can be configured by modifying the `application.properties` file in the `src/main/resources` directory.

## Contributing

1. Fork the repository
2. Create a feature branch: `git checkout -b feature/your-feature-name`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin feature/your-feature-name`
5. Open a pull request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- Thanks to all contributors who have helped with the development of this application
- Special thanks to the Spring Boot and Java communities for their excellent documentation and support
