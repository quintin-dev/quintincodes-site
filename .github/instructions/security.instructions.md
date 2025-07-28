---
description: "Security guidelines and best practices"
applyTo: "**"
---

# Security Standards

## Input Validation
- Validate and sanitize all user inputs
- Use parameterized queries to prevent SQL injection
- Implement proper authentication and authorization
- Use HTTPS for all data transmission

## Data Protection
- Never commit secrets or API keys to version control
- Use environment variables for sensitive configuration
- Implement proper session management
- Follow OWASP security guidelines

## Code Security
- Keep dependencies updated and scan for vulnerabilities
- Implement Content Security Policy (CSP)
- Use secure coding practices
- Regular security audits and penetration testing

## API Security
- Implement rate limiting
- Use proper CORS configuration
- Validate API tokens and permissions
- Log security events for monitoring
