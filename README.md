# Book Selling .NET Project

This project is a book selling application developed using .NET framework. It provides a platform for users to browse, search, and purchase books online. The application includes features such as user registration, book catalog management, shopping cart functionality, and order processing.

## Requirements

- Download [SQL Server Management Studio (SSMS)](https://learn.microsoft.com/en-us/sql/ssms/download-sql-server-management-studio-ssms?view=sql-server-ver16).
- Connect to SQL Server:
  - Server Type: Database Engine
  - Server Name: (localdb)\MSSQLLocalDB
  - Authentication: Windows Authentication

## Installation

1. Download and install SQL Server Management Studio (SSMS) from the [official website](https://learn.microsoft.com/en-us/sql/ssms/download-sql-server-management-studio-ssms?view=sql-server-ver16).

## Getting Started

To run the Book Selling application locally, follow these steps:

1. Clone the repository.
2. Open the solution file in Visual Studio.
3. Build the solution to restore dependencies and compile the project.
4. Open SQL Server Management Studio and connect to the local database server.
5. Execute the SQL scripts provided in the `Database` folder to create the necessary database schema.
6. Update the database connection string in the project configuration file (`appsettings.json`) with your local database details.
7. Open the Package Manager Console in Visual Studio: `Tools -> NuGet Package Manager -> Package Manager Console`.
8. In the Package Manager Console, run the following commands:
   - `add-migration InitMigrationToDB`
   - `update-database`
9. Run the application using Visual Studio, or publish it to a web server.

## Usage

Once the application is running, you can access it through your web browser. The application allows users to:
- Browse the book catalog, view book details, and read book reviews.
- Search for books based on various criteria such as title, author, genre, etc.
- Add books to the shopping cart and proceed to checkout.
- Manage user profile, including order history and account settings.

Feel free to explore the application and test its functionalities.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

## License

This project
