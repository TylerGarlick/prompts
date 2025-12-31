# Architecture Review

## System Overview
System: [SYSTEM_NAME]
Type: [MONOLITH/MICROSERVICES/SERVERLESS/etc.]
Scale: [USER_SCALE/DATA_SCALE]

## Current Architecture
Components:
1. [COMPONENT_1]: [DESCRIPTION]
2. [COMPONENT_2]: [DESCRIPTION]
3. [COMPONENT_3]: [DESCRIPTION]

Technology stack: [TECH_STACK]

## Architecture Diagram/Description
```
[ASCII_DIAGRAM_OR_DESCRIPTION]
```

## Requirements
- Performance: [REQUIREMENTS]
- Scalability: [REQUIREMENTS]
- Availability: [REQUIREMENTS]
- Security: [REQUIREMENTS]
- Compliance: [REQUIREMENTS]

## Concerns/Questions
[SPECIFIC_CONCERNS_OR_QUESTIONS]

## Request
Review the architecture and provide feedback on:

**Design Principles:**
1. Separation of concerns
2. Single Responsibility Principle
3. Don't Repeat Yourself (DRY)
4. SOLID principles adherence
5. Loose coupling, high cohesion

**Scalability:**
1. Horizontal vs vertical scaling approach
2. Stateless design where appropriate
3. Database sharding/partitioning strategy
4. Caching strategy
5. Load balancing approach
6. Auto-scaling capabilities

**Reliability:**
1. Single points of failure
2. Fault tolerance mechanisms
3. Circuit breaker patterns
4. Retry logic and backoff strategies
5. Graceful degradation

**Performance:**
1. Latency considerations
2. Throughput optimization
3. Resource utilization efficiency
4. Bottleneck identification

**Security:**
1. Defense in depth
2. Least privilege principle
3. Data encryption strategy
4. Network segmentation
5. API security

**Maintainability:**
1. Code organization
2. Modularity
3. Dependency management
4. Technical debt assessment

**Observability:**
1. Logging strategy
2. Monitoring and alerting
3. Distributed tracing
4. Metrics collection

**Data Architecture:**
1. Data storage choices
2. Data consistency model
3. Backup and recovery strategy
4. Data migration approach

**Integration:**
1. API design patterns
2. Service communication
3. Event-driven architecture
4. Message queuing

Provide:
- Strengths of current design
- Weaknesses and risks
- Specific improvement recommendations
- Alternative approaches
- Migration strategy if major changes needed
