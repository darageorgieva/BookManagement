Book Management App

This is a ASP.NET Core MVC application that allows users to:

Add books

Add genres

Associate books with genres

Features

Book Management: Add and manage books.

Genre Management: Create and organize book genres.

Book-Genre Association: Link books to genres.

Installation & Setup

Prerequisites

.NET 6+

SQL Server (or SQLite for development)

Steps

Clone the repository:

git clone https://github.com/yourusername/BookManagement.git
cd BookManagement

Install dependencies:

dotnet restore

Set up the database:

dotnet ef database update

Run the application:

dotnet run

Project Structure

Controllers/: Handles request logic.

Models/: Defines data structures.

Views/: Contains UI templates.

Data/: Handles database operations.

Migrations/: Stores Entity Framework migrations.

wwwroot/: Static assets (CSS, JS, images, etc.).

appsettings.json: Configuration settings.

Usage

Navigate to http://localhost:5000 (or as specified in the console).

Use the interface to add books and genres.

Associate books with genres.

Contributing

Feel free to open issues and submit pull requests!

License

MIT

