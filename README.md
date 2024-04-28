# APIWeatherTesting
Test Plan
Test Objectives:
Validate the functionality of the APIs for retrieving current weather data.
Verify the accuracy and consistency of weather data returned by the APIs.
Ensure proper error handling and response status codes.
Evaluate the performance and responsiveness of the APIs under varying conditions.

Test Environment:
Programming Language: Python
Testing Framework: Pytest
APIs Under Test: OpenWeatherMap
Test Scenarios:
Positive Test Scenarios
Scenario: Retrieve current weather by city name
Input: Valid city name (e.g., London)
Expected Outcome: API returns current weather data for the specified city.
Test Scenarios:
Negative Test Scenarios
Scenario: Retrieve weather for an invalid city name
Input: Invalid city name (e.g., Abcdefgh)
Expected Outcome: API returns an appropriate error response (404 Not Found).



