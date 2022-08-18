# Fundamentals of software architecture

## Architecture characteristics

- Availability
- Performance
- Security
- Requirements
- Data
- Legality
- Scalability
- Testability
- Learnability

## Definition of function

When implementing any function in application, there are multiple questions to be answered before start development:
- How this peace of code will be unit-tested?
- How to write integration tests for this function?
  - Do we run integration tests in isolated environment?
  - If not in isolated environment - how delete produced data after tests are completed?
- Is this functionality secure enogh?
  - Does access to functionality is secure?
  - Does function requires authorization as well?
  - Does data complies with data protection, Sarbanes Oxey, GDPR, etc.?
