# Integration testing of API Controllers with NUnit and xUnit
![image](https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=csharp&logoColor=white)
![image](https://img.shields.io/badge/.NET-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)
![image](https://img.shields.io/badge/Visual_Studio-5C2D91?style=for-the-badge&logo=visual%20studio&logoColor=white)
### This is a test project for Back-End Test Automation March 2024 Course @ SoftUni.
---
## About
This repository showcases integration testing of API controllers in an ASP.NET MVC project using NUnit and xUnit frameworks.

## Project Goal

This project demonstrates how to write integration tests to verify the functionality of API controllers interacting with a database (e.g., SQL Server via SSMS).

## Testing Frameworks

- NUnit: A mature and popular .NET testing framework.
- xUnit: A free and open-source testing framework known for its readability and ease of use.
  
## Prerequisites
- Basic understanding of ASP.NET MVC, C#, and web APIs.
- Familiarity with NUnit or xUnit (choose one or both).
- Familiarity with SSMS(SQL Server Management Studio).
  
## Project Structure
- Controllers: This folder holds the code for controllers, which handle incoming and outgoing API requests and interact with the application logic and data layer.
- Models: This folder contains classes representing the data models used by the application. These models define the data structure (e.g., Event, User, etc.).
- Properties: This folder contains configuration files specific to the environment, such as connection strings and other settings.
- Views: This folder holds the code for the user interface (UI) elements, such as Razor views for ASP.NET MVC applications.
- Tests: This file contains integration tests for the "Eventmi" app.
  
## Understanding the Application (Brief Summary)
- The application under test is an ASP.NET MVC project named "Eventmi".
- The application is interacting with a database managed through SSMS.
- Since It manages events, my main focus was on writing API tests for this functionality.

## Why Not Use a Constructor
While you could theoretically use a constructor in a test class to initialize fields, it's not the standard practice for a few reasons:
- Consistency: NUnit's setup and teardown methods `[SetUp]` and `[TearDown]` provide a consistent way to initialize and clean up resources before and after each test. They're designed to work with NUnit's test lifecycle
- Flexibility: Using `[SetUp]` allows for more complex setup logic that might involve reading from configuration files, setting up mocks, or any other actions you'd want to perform before each test.
- Isolation: `[SetUp]` ensures that the state is reset before each test, providing better test isolation and reducing the risk of inter-test dependencies.
  
## Additional Notes
- This repository serves as a starting point for testing integration of API controllers.
- This repository demonstrates xUnit and NUnit configuration and usage with the "Eventmi" application file.
- The specific setup and configuration steps might vary depending on the project's implementation.

## Contributing
Contributions are welcome! If you have any improvements or bug fixes, feel free to open a pull request.

## License
This project is licensed under the [MIT License](LICENSE). See the [LICENSE](LICENSE) file for details.

## Contact
For any questions or suggestions, please open an issue in the repository.
