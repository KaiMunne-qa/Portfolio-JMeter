# JMeter Performance Testing Portfolio

## Overview
This portfolio showcases my ability to design and execute performance and functional tests using Apache JMeter. It includes a comprehensive test plan created for a flight booking interface (*Blaze Demo*), demonstrating core skills in load testing, parameterization, and result analysis.

## Test Plan: Use of Interface - Blaze Demo

### Objectives
The test plan evaluates the performance and reliability of key workflows in the flight booking application, focusing on:
- Search functionality for flights.
- Flight selection and booking confirmation.

### Key Features
1. **Dynamic and Parameterized Testing**:
   - Utilized variables like (`${Origin}`, `${nameOnCard}`) for flexible and reusable test scripts.
   - Integrated a CSV Data Set Config to supply test data dynamically during execution.
2. **HTTP Samplers**:
   - Search flights by origin.
   - Select a specific flight.
   - Confirm booking details.
3. **Assertions**:
   - Included a JSR223 Assertion to verify that the data used in the POST requests matches the expected values from the test data.
   - Validated response content to ensure correct application behavior.

## Results
The test results demonstrate:
- Consistent response times for search and booking operations.
- Application stability under simulated load.
- Successful validation of POST request data through assertions.

### HTML Report
The results are presented in a detailed HTML report, which includes:
- Response time distribution.
- Throughput and error rate analysis.
- Summary of successful and failed requests.

### Sample Output
Include links or screenshots of:
- Test results from the HTML report.
- Assertions that validate successful transactions.

## Files
- `useOfInterfaceBlazeDemo.jmx`: The JMeter test plan. 
- `/Destination:  Contains the CSV file used for select diffents destinations.
- `/PersonalData`: Contains the CSV file used for confirmation data in the tests.
- `/results`: Contains the HTML report generated from the tests.

## Conclusion
This project demonstrates my ability to:
- Design end-to-end performance tests.
- Work with dynamic test data using CSV configurations.
- Implement custom assertions for advanced validation.
- Analyze results to ensure application reliability.

## Next Steps
Future iterations could include:
- Testing additional workflows.
- Expanding load conditions for stress testing.

---

Feel free to explore the test plan and results to understand the detailed implementation.
