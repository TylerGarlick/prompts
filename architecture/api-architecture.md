# API Architecture

## API Context
API Name: [API_NAME]
Purpose: [PURPOSE]
Consumers: [WHO_WILL_USE_IT]

## Requirements
- Expected traffic: [REQUESTS_PER_SECOND]
- Response time: [TARGET_LATENCY]
- Data types: [DATA_TYPES_SERVED]
- Authentication: [AUTH_REQUIREMENTS]
- Versioning needs: [VERSIONING_STRATEGY]

## Use Cases
Main operations:
1. [OPERATION_1]: [DESCRIPTION]
2. [OPERATION_2]: [DESCRIPTION]
3. [OPERATION_3]: [DESCRIPTION]

## Constraints
- Technology stack: [PREFERRED_STACK]
- Backward compatibility: [REQUIREMENTS]
- Rate limiting: [REQUIREMENTS]
- Caching: [REQUIREMENTS]

## Request
Design a comprehensive API architecture including:

**API Style Selection:**
1. REST vs GraphQL vs gRPC vs WebSocket
2. Rationale for choice
3. Hybrid approach if needed

**For REST APIs:**

**Endpoint Design:**
1. Resource naming conventions
2. URL structure
3. HTTP methods usage (GET, POST, PUT, PATCH, DELETE)
4. Resource hierarchies
5. Query parameters vs path parameters

**Request/Response Format:**
1. JSON schema definitions
2. Request validation rules
3. Response structure standards
4. Error response format
5. Pagination approach (cursor vs offset)
6. Filtering and sorting
7. Field selection/sparse fieldsets

**For GraphQL APIs:**

**Schema Design:**
1. Type definitions
2. Query design
3. Mutation design
4. Subscription design (if applicable)
5. Input types
6. Custom scalars

**For All APIs:**

**Authentication & Authorization:**
1. Authentication mechanism (JWT, OAuth2, API keys)
2. Authorization strategy (RBAC, ABAC)
3. Token management
4. Scope definition
5. Security headers

**Versioning:**
1. Versioning strategy (URL, header, content negotiation)
2. Deprecation policy
3. Backward compatibility approach
4. Migration path for consumers

**Rate Limiting:**
1. Rate limit strategy
2. Throttling approach
3. Quota management
4. Response headers for limits

**Caching:**
1. Cache-Control headers
2. ETags
3. Conditional requests
4. CDN integration

**Error Handling:**
1. Error code structure
2. Error messages format
3. Validation errors
4. Standard HTTP status codes usage
5. Error documentation

**Documentation:**
1. OpenAPI/Swagger specification
2. Interactive documentation
3. Code examples
4. Authentication guide
5. Changelog

**Performance:**
1. Response compression
2. Batch operations
3. Async operations for long-running tasks
4. Webhooks for notifications
5. Connection pooling

**Monitoring & Analytics:**
1. Logging strategy
2. Metrics to track
3. Tracing implementation
4. Analytics for API usage

**API Gateway:**
1. Gateway pattern usage
2. Cross-cutting concerns handling
3. Request routing
4. Protocol translation

**Testing:**
1. Contract testing approach
2. Integration testing
3. Load testing strategy
4. Mock server for development

**Governance:**
1. API standards
2. Review process
3. Lifecycle management
4. Deprecation process

Provide:
- API specification (OpenAPI/GraphQL schema)
- Example requests and responses
- Integration examples
- Best practices specific to chosen style
