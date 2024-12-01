# Login System

A professional ASP.NET Core MVC web application implementing a secure login system. This project was developed as part of a practical examination to demonstrate proficiency in web development, security implementation, and MVC architectural patterns.

## Features

- MVC (Model-View-Controller) Architecture
- User authentication and authorization
- Secure password handling
- Modern and responsive user interface
- Clean separation of concerns
- Data validation and model binding

## Technologies Used

- ASP.NET Core MVC
- C#
- Entity Framework Core
- HTML/CSS
- JavaScript
- Bootstrap (for responsive design)
- SQL Server

## Architecture

This project follows the MVC (Model-View-Controller) pattern:

### Models
- Handle data logic and business rules
- Define database structure
- Implement data validation

### Views
- Present data to users
- Handle user interface elements
- Implement responsive design
- Use Razor syntax for dynamic content

### Controllers
- Process incoming requests
- Handle user input
- Manage application flow
- Return appropriate responses

## Getting Started

### Prerequisites

- .NET SDK (latest version)
- Visual Studio 2019/2022 or VS Code
- SQL Server (LocalDB or higher)

### Installation

1. Clone the repository
   ```bash
   git clone [repository-url]
   ```

2. Navigate to the project directory
   ```bash
   cd Practical__Login
   ```

3. Restore dependencies
   ```bash
   dotnet restore
   ```

4. Update database with migrations
   ```bash
   dotnet ef database update
   ```

5. Run the application
   ```bash
   dotnet run
   ```

The application will be available at `https://localhost:5001` or `http://localhost:5000`

## Project Structure

```
Practical__Login/
├── Controllers/         # Handle user requests and application flow
├── Models/             # Data models and business logic
├── Views/              # Razor views for UI
├── wwwroot/           # Static files (CSS, JS, images)
└── Program.cs         # Application entry point
```

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Author

Khadalicioso

---
*This project was created as part of an academic practical examination demonstrating MVC architecture principles.*
