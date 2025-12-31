# API Development

## API Specification
Endpoint: [HTTP_METHOD] [ENDPOINT_PATH]
Purpose: [API_PURPOSE]

## Request Details
Headers:
- [HEADER_1]: [VALUE]
- [HEADER_2]: [VALUE]

Body (JSON):
```json
{
  "field1": "type/example",
  "field2": "type/example"
}
```

Query parameters:
- [PARAM_1]: [DESCRIPTION]
- [PARAM_2]: [DESCRIPTION]

## Response Details
Success (200):
```json
{
  "status": "success",
  "data": {}
}
```

Errors:
- 400: [CONDITION]
- 401: [CONDITION]
- 404: [CONDITION]
- 500: [CONDITION]

## Requirements
- Authentication: [AUTH_METHOD]
- Rate limiting: [RATE_LIMITS]
- Validation rules: [VALIDATION_REQUIREMENTS]
- Database operations: [DB_OPERATIONS]

## Request
Help me implement this API endpoint including:
1. Route handler/controller code
2. Request validation and sanitization
3. Business logic implementation
4. Database queries (with ORM/raw SQL)
5. Error handling and appropriate status codes
6. Response formatting
7. Authentication/authorization checks
8. Logging for debugging
9. API documentation comments

Framework: [FRAMEWORK_NAME]
Database: [DATABASE_TYPE]
