# End-to-End Test Scenarios

## Application
Name: [APP_NAME]
Type: [WEB/MOBILE/DESKTOP]
URL/Access: [URL_OR_ACCESS_METHOD]

## User Journey
Journey name: [JOURNEY_NAME]
User persona: [PERSONA_DESCRIPTION]

Steps:
1. [STEP_1]
2. [STEP_2]
3. [STEP_3]
...

Expected result: [FINAL_OUTCOME]

## Test Environment
- Browser/Platform: [BROWSERS]
- Test data: [TEST_DATA_SOURCE]
- Authentication: [AUTH_DETAILS]

## Testing Framework
Framework: [SELENIUM/PLAYWRIGHT/CYPRESS/etc.]
Language: [LANGUAGE]

## Request
Create E2E test automation code that:
1. Sets up the test environment
2. Navigates through the user journey
3. Interacts with UI elements (clicks, typing, etc.)
4. Validates expected outcomes at each step
5. Handles waits and asynchronous operations
6. Takes screenshots on failures
7. Cleans up test data after execution
8. Includes retry logic for flaky tests
9. Provides clear test reports

Include:
- Page object model (if applicable)
- Reusable helper functions
- Data-driven test variations
- Cross-browser considerations
