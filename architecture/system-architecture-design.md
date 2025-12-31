# System Architecture Design

## Project Requirements
Project: [PROJECT_NAME]
Type: [WEB_APP/MOBILE_APP/API/PLATFORM/etc.]
Description: [PROJECT_DESCRIPTION]

## Functional Requirements
1. [REQUIREMENT_1]
2. [REQUIREMENT_2]
3. [REQUIREMENT_3]

## Non-Functional Requirements
- **Performance:**
  - Expected users: [NUMBER]
  - Requests per second: [RPS]
  - Response time: [TARGET_LATENCY]
  
- **Scalability:**
  - Growth projection: [GROWTH_RATE]
  - Peak load: [PEAK_LOAD]
  
- **Availability:**
  - Uptime target: [SLA_PERCENTAGE]
  - Disaster recovery: [RTO/RPO]
  
- **Security:**
  - Compliance: [COMPLIANCE_REQUIREMENTS]
  - Data sensitivity: [SENSITIVITY_LEVEL]

## Constraints
- Budget: [BUDGET_CONSTRAINTS]
- Timeline: [TIMELINE]
- Technology preferences: [TECH_PREFERENCES]
- Team expertise: [TEAM_SKILLS]
- Legacy systems: [INTEGRATION_NEEDS]

## Request
Design a comprehensive system architecture including:

**High-Level Architecture:**
1. Overall architecture diagram
2. Component breakdown
3. Data flow diagram
4. Integration points
5. Architecture style (microservices/monolith/serverless/hybrid)

**Technology Stack:**
For each layer recommend:
1. **Frontend:**
   - Framework/library
   - State management
   - Build tools
   
2. **Backend:**
   - Programming language
   - Framework
   - API design (REST/GraphQL/gRPC)
   
3. **Database:**
   - Primary database type and choice
   - Caching layer
   - Search engine (if needed)
   
4. **Infrastructure:**
   - Cloud provider
   - Container orchestration
   - Service mesh (if applicable)
   
5. **DevOps:**
   - CI/CD platform
   - Monitoring/logging
   - Infrastructure as Code tool

**Component Design:**
For each major component:
1. Responsibilities
2. APIs/interfaces
3. Dependencies
4. Data models
5. Scaling strategy

**Data Architecture:**
1. Data storage strategy
2. Data partitioning/sharding
3. Data replication
4. Backup and recovery
5. Data migration approach

**Security Architecture:**
1. Authentication/authorization strategy
2. Network security
3. Data encryption (at rest and in transit)
4. API security
5. Secrets management
6. Compliance measures

**Scalability Design:**
1. Horizontal scaling strategy
2. Load balancing approach
3. Caching strategy (CDN, application, database)
4. Database scaling (read replicas, sharding)
5. Asynchronous processing
6. Queue management

**Reliability Design:**
1. Fault tolerance mechanisms
2. Circuit breakers
3. Retry policies
4. Graceful degradation
5. Health checks
6. Disaster recovery plan

**Observability:**
1. Logging strategy
2. Metrics collection
3. Distributed tracing
4. Alerting strategy
5. Dashboard design

**Development Approach:**
1. Monorepo vs multi-repo
2. Branching strategy
3. Deployment strategy
4. Testing strategy
5. Documentation approach

**Migration/Implementation Plan:**
1. Phased rollout approach
2. Proof of concept recommendations
3. MVP scope
4. Risk mitigation
5. Success metrics

Provide:
- Architecture diagrams (text/Mermaid/ASCII)
- Rationale for key decisions
- Trade-offs and alternatives considered
- Cost estimates if possible
- Implementation timeline
