API Testing the Student Management System
Tested By:
Md. Tazveer Hossain Khan

Project Overview
This project focuses on testing the Student Management System (SMS) API to ensure its functionality, security, and performance. The API is tested using Postman and automated test scripts.

Project Structure
SQA API Testing/
│── docs/                     # Contains test case documents and reports
│── postman/                  # Contains Postman collections and environment files
│── src/                      # Source code for the API
│── requirement.pdf            # API requirements document
│── .gitignore                 # Files to ignore in version control
│── README.md                 # Project documentation (this file)
Prerequisites
Ensure you have the following installed before running tests:

Python 3.x
Postman
VS Code
Setup Instructions
1. Clone the Repository
git clone <repository-url>
cd SQA-API-Testing

2. Import Postman Collection & Environment
Open Postman.
Go to File → Import.
Select student_api_collection.json from the postman/ folder.
Select student_api_environment.json to set up the environment variables.
3. Run API Tests
Manual Testing in Postman
Open Postman and execute API requests.
Check responses, status codes, and validations.

Test Case Documentation
All test cases are documented in the docs/ folder as a PDF. It includes:

Test scenarios
Input data
Expected vs actual results
Contributing
Fork the repository
Create a new branch (feature-branch)
Commit your changes
Submit a pull request
License
This project is for educational purposes.

This README follows best practices for an SQA API Testing project. Let me know if you need modifications! 🚀