# Microservices Design

## Context
System: [SYSTEM_NAME]
Current state: [MONOLITH/NEW_PROJECT]

## Business Capabilities
Main business domains:
1. [DOMAIN_1]
2. [DOMAIN_2]
3. [DOMAIN_3]

## Current Monolith (if applicable)
```
[HIGH_LEVEL_DESCRIPTION_OR_DIAGRAM]
```

Current issues:
- [ISSUE_1]
- [ISSUE_2]

## Requirements
- Team structure: [TEAM_STRUCTURE]
- Deployment frequency: [FREQUENCY]
- Scalability needs: [NEEDS]
- Data isolation: [REQUIREMENTS]

## Request
Help me design a microservices architecture:

**Service Decomposition:**
1. Identify microservices based on:
   - Business capabilities
   - Domain-driven design
   - Bounded contexts
   - Data ownership

2. For each proposed service:
   - Name and purpose
   - Responsibilities
   - API contracts
   - Data ownership
   - Dependencies on other services

**Service Boundaries:**
1. How to define clear boundaries
2. Shared vs service-specific data
3. Service coupling analysis
4. Service cohesion validation

**Communication Patterns:**
1. Synchronous vs asynchronous
2. API Gateway pattern
3. Service mesh considerations
4. Event-driven architecture
5. Message broker selection
6. API versioning strategy

**Data Management:**
1. Database per service pattern
2. Saga pattern for transactions
3. Event sourcing (if applicable)
4. CQRS (if applicable)
5. Data consistency strategy
6. Data replication approach

**Cross-Cutting Concerns:**
1. Authentication/authorization
2. Service discovery
3. Configuration management
4. Logging and monitoring
5. Distributed tracing
6. Circuit breakers
7. Rate limiting

**Deployment:**
1. Containerization strategy
2. Orchestration platform (Kubernetes, etc.)
3. CI/CD pipeline per service
4. Blue-green deployment
5. Canary releases
6. Service versioning

**Testing Strategy:**
1. Unit testing per service
2. Integration testing
3. Contract testing
4. End-to-end testing
5. Chaos engineering

**Migration Strategy (if from monolith):**
1. Strangler pattern approach
2. Service extraction priority
3. Database decomposition
4. Phased rollout
5. Risk mitigation
6. Rollback strategy

**Organizational Impact:**
1. Team structure alignment
2. Service ownership model
3. Communication patterns
4. Documentation needs

**Challenges & Solutions:**
Address common challenges:
1. Distributed system complexity
2. Data consistency
3. Testing complexity
4. Operational overhead
5. Service discovery
6. Debugging distributed systems

Provide:
- Service inventory with descriptions
- Communication diagram
- Data architecture diagram
- Migration timeline (if applicable)
- Team topology recommendations
