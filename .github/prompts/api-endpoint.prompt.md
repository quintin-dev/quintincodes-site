---
mode: "edit"
tools: ["filesystem", "terminal"]
description: "Generate API endpoint with validation and testing"
---

# Create API Endpoint

Generate a complete API endpoint with the following specifications:

## Endpoint Details
- **Path**: ${input:path:Enter API path (e.g., /api/users)}
- **Method**: ${input:method:GET, POST, PUT, DELETE, PATCH}
- **Purpose**: ${input:purpose:Describe what this endpoint does}

## Requirements
- Input validation with appropriate schema
- Error handling with proper HTTP status codes
- Authentication/authorization checks
- Rate limiting considerations
- Comprehensive API documentation
- Unit and integration tests
- TypeScript interfaces for request/response

## Generate
1. Controller/handler function
2. Request/response type definitions
3. Validation schema
4. Unit tests
5. Integration tests
6. API documentation (OpenAPI/Swagger)
7. Error handling middleware

Follow RESTful conventions and project patterns.
Include proper logging and monitoring hooks.
