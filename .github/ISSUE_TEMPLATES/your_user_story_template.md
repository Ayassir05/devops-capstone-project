**As a** Software Engineer
**I need** a logging mechanism for user authentication failures
**So that** I can monitor and investigate potential security threats.

### Details and Assumptions
* The logging mechanism should capture user details (username, IP address, timestamp).
* Use a standardized log format compatible with our centralized logging system.

### Acceptance Criteria
```gherkin
Given a user attempts to authenticate
When the authentication fails
Then the system should log the user details, IP address, and timestamp in the standardized format.
