# Login System

A professional ASP.NET Core MVC web application implementing a secure login system with a modern, sleek user interface. This project showcases contemporary web development practices, combining robust security with an engaging user experience through smooth animations and responsive design.

## Features

- Modern, professional UI with smooth animations
- Responsive design that works across all devices
- Clean, gradient-based color scheme
- Elegant transitions and hover effects
- Cross-browser compatible animations
- MVC (Model-View-Controller) Architecture
- User authentication and authorization
- Secure password handling
- Clean separation of concerns
- Data validation and model binding

## Technologies Used

- ASP.NET Core MVC
- C#
- Entity Framework Core
- HTML5/CSS3 (with modern animations)
- JavaScript
- Bootstrap 4.1.1
- Font Awesome 5.15.4
- SQL Server

## UI Features

- Smooth fade-in animations
- Modern gradient backgrounds
- Responsive card layouts
- Professional typography
- Consistent color scheme
- Interactive hover effects
- Clean icon integration
- Mobile-first design approach

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
   git clone https://github.com/Khadalicioso/login_system.git
   ```

2. Navigate to the project directory
   ```bash
   cd login_system
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
login/
├── Controllers/         # Handle user requests and application flow
├── Models/             # Data models and business logic
├── Views/              # Razor views for UI
├── wwwroot/           
│   ├── css/           # Stylesheets including modern animations
│   ├── js/            # JavaScript enhancements
│   └── images/        # Visual assets
└── Program.cs         # Application entry point
```

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Author

Khadalicioso

---
*This project demonstrates modern web development practices, combining secure authentication with contemporary UI/UX design principles.*
