# Selenium NUnit Example

This project demonstrates how to use Selenium WebDriver with NUnit for automated web testing, specifically for testing Google search functionality.

## Prerequisites

- .NET Framework
- NUnit
- Selenium WebDriver
- ChromeDriver

## Project Structure

The project consists of the following main components:

1. `GoogleSearchTest.cs`: The main test class containing the test methods.
2. `GoogleHomePage.cs`: Page Object for Google's home page (not shown in the provided code).
3. `GoogleResultsPage.cs`: Page Object for Google's search results page (not shown in the provided code).

## Test Scenario

The test performs the following steps:

1. Navigates to Google's homepage.
2. Verifies the page title.
3. Performs a search for "Selenium WebDriver".
4. Verifies that search results are displayed.
5. Clicks on the first search result.
6. Verifies the title of the new page.
7. Navigates back to the search results.
8. Verifies that the search term is still present in the search box.

## Running the Tests

To run the tests:

1. Ensure that ChromeDriver is installed and its path is correctly set in the `SetUp` method.
2. Build the project.
3. Run the tests using NUnit test runner.

