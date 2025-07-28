---
description: "Testing standards and practices"
applyTo: "**/test/**,**/*.test.*,**/*.spec.*"
---

# Testing Standards

## Test Structure
- Use Arrange-Act-Assert (AAA) pattern
- Write descriptive test names that explain the scenario
- Group related tests using describe blocks
- Use beforeEach/afterEach for setup and cleanup

## Coverage Requirements
- Aim for 80%+ code coverage
- Test happy paths and edge cases
- Include error scenario testing
- Test user interactions and accessibility

## Testing Tools
- Use Jest for unit testing
- Use React Testing Library for component testing
- Use Cypress or Playwright for E2E testing
- Mock external dependencies appropriately

## Best Practices
- Test behavior, not implementation details
- Write tests that are easy to read and maintain
- Use data-testid for reliable element selection
- Keep tests independent and isolated
