# Integration testing of API Controllers with NUnit and XUnit
## This is a test project for Back-End Test Automation March 2024 Course @ SoftUni.
This repository showcases integration testing of API controllers in an ASP.NET MVC project using NUnit and xUnit frameworks.
### Project Goal:

This project demonstrates how to write integration tests to verify the functionality of API controllers interacting with a database (e.g., SQL Server via SSMS).

### Testing Frameworks:

- NUnit: A mature and popular .NET testing framework.
- xUnit: A free and open-source testing framework known for its readability and ease of use.
### Prerequisites:

- Basic understanding of ASP.NET MVC, C#, and web APIs.
- Familiarity with NUnit or xUnit (choose one or both).
- Familiarity with SSMS(SQL Server Management Studio).
### Project Structure:
- Controllers: This folder holds the code for controllers, which handle incoming and outgoing API requests and interact with the application logic and data layer.
- Models: This folder contains classes representing the data models used by the application. These models define the data structure (e.g., Event, User, etc.).
- Properties: This folder contains configuration files specific to the environment, such as connection strings and other settings.
- Views: This folder holds the code for the user interface (UI) elements, such as Razor views for ASP.NET MVC applications.
- wwwroot: This folder holds static content that can be accessed directly by the web server, such as images, CSS files, or JavaScript files.
- Tests: This file contains integration tests for the "Eventmi" app
### Understanding the Application (Brief Summary):

- The application under test is an ASP.NET MVC project named "Eventmi".
- The application is interacting with a database managed through SSMS.
- Since It manages events, my main focus was on writing API tests for this functionality.
  
### Additional Notes:
- This repository serves as a starting point for learning integration testing of API controllers.
- This repository demonstrates XUnit and NUnit configuration and usage with the "Eventme" application file.
- The specific setup and configuration steps might vary depending on the project's implementation.
### Contributing
Contributions are welcome! If you have any improvements or bug fixes, feel free to open a pull request.

### License
This project is licensed under the MIT License. See the LICENSE file for details.

### Contact
For any questions or suggestions, please open an issue in the repository.
