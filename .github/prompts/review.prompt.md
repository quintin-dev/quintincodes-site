---
mode: "ask"
description: "Comprehensive code review checklist"
---

# Code Review Checklist

Perform a thorough code review of the current selection or file, focusing on:

## Code Quality
- **Readability**: Is the code easy to understand?
- **Maintainability**: Will this be easy to modify in the future?
- **Performance**: Are there any performance concerns?
- **Security**: Any security vulnerabilities or concerns?

## Best Practices
- **Design Patterns**: Are appropriate patterns being used?
- **Error Handling**: Is error handling comprehensive?
- **Testing**: Are there adequate tests?
- **Documentation**: Is the code well-documented?

## Technical Concerns
- **Dependencies**: Are dependencies necessary and up-to-date?
- **Scalability**: Will this scale with increased usage?
- **Accessibility**: Does this meet accessibility standards?
- **Browser Compatibility**: Any compatibility issues?

## Specific Checks
- Code follows project conventions
- No console.log statements in production code
- Proper TypeScript types are used
- Functions are not too complex (cognitive complexity)
- No magic numbers or strings
- Proper naming conventions

Provide specific, actionable feedback with code examples where appropriate.
