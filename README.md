# Katalon API Automation Testing for OpenWeatherMap

This project contains automation test cases for the OpenWeatherMap API, implemented using Katalon Studio. The tests include the following scenarios:

1. Get the 5-day weather forecast for Jakarta Selatan.
2. Get the current air pollution data for Jakarta Selatan.

## Steps to Run the Project

1. **Clone the repository**:
   ```bash
   git clone https://github.com/Leons0408/TestWeather.git



Open the project in Katalon Studio:

Launch Katalon Studio.
Open the project by selecting File > Open Project and navigate to the folder where you cloned the repository.
Run the test cases:

Go to Test Cases folder.
Right-click on the test case and click Run.
The API requests will be executed, and results will be displayed in the Log Viewer.

View the report:
Run the test suit, then navigate to the Reports folder.
Open the index.html file in your browser to view the test execution report.


Project Structure
The project is organized into the following folders:

/Drivers/: Contains browser drivers (not used for API tests).
/Object Repository/: Stores UI objects (not used for API tests).
/Reports/: Stores test execution reports.
/Scripts/:
Test Cases: Stores individual test cases (e.g., weather forecast and air pollution test cases).
Test Suites: Stores test suites (groups of test cases).
Test Data: Contains test data files (CSV, Excel, etc.).
/Profiles/: Stores configuration profiles (e.g., API keys).
/Include/: Stores global variables and utility scripts.
