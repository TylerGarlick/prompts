# Database Schema Design

## Project Context
Application: [APP_NAME]
Type: [APP_TYPE]
Expected scale: [USER_COUNT/DATA_VOLUME]

## Business Requirements
Main entities and relationships:
1. [ENTITY_1]: [DESCRIPTION]
2. [ENTITY_2]: [DESCRIPTION]
3. [RELATIONSHIP]: [DESCRIPTION]

## Use Cases
Primary operations:
1. [USE_CASE_1]: [FREQUENCY]
2. [USE_CASE_2]: [FREQUENCY]
3. [USE_CASE_3]: [FREQUENCY]

## Requirements
- Read vs Write ratio: [RATIO]
- Query patterns: [PATTERNS]
- Transaction requirements: [ACID/EVENTUAL_CONSISTENCY]
- Data retention: [RETENTION_POLICY]
- Compliance: [REQUIREMENTS]

## Database Type
Preference: [RELATIONAL/DOCUMENT/GRAPH/TIME_SERIES/etc.]
Or request recommendation

## Request
Design a database schema that includes:

**For Relational Databases:**

**Schema Design:**
1. Table definitions with:
   - Table names
   - Columns (name, type, constraints)
   - Primary keys
   - Foreign keys
   - Indexes
   - Constraints (unique, check, etc.)

2. Relationships:
   - One-to-many
   - Many-to-many (junction tables)
   - One-to-one

3. Normalization:
   - Normal form achieved (1NF, 2NF, 3NF, BCNF)
   - Denormalization decisions
   - Rationale for trade-offs

**For NoSQL Databases:**

**Data Model:**
1. Document/collection structure
2. Embedding vs referencing decisions
3. Denormalization strategy
4. Sharding key selection

**Common Elements:**

**Query Optimization:**
1. Index strategy
2. Query patterns supported
3. Performance considerations
4. Partitioning strategy

**Data Integrity:**
1. Validation rules
2. Referential integrity
3. Transaction boundaries
4. Concurrency control

**Scalability:**
1. Partitioning/sharding strategy
2. Read replicas
3. Caching strategy
4. Archive strategy

**Security:**
1. Data encryption
2. Access control
3. PII handling
4. Audit logging

**Migration Strategy:**
1. Schema versioning approach
2. Migration scripts structure
3. Backward compatibility
4. Rollback procedures
5. Zero-downtime migration approach

**Sample Queries:**
Provide optimized queries for:
1. Common read operations
2. Common write operations
3. Complex aggregations
4. Reporting queries

**DDL Scripts:**
Include:
1. CREATE TABLE statements
2. CREATE INDEX statements
3. Constraints
4. Initial data (if applicable)

**Documentation:**
1. Entity-Relationship diagram
2. Data dictionary
3. Indexing strategy explanation
4. Query optimization notes

Ensure the design:
- Supports all use cases efficiently
- Scales with growth
- Maintains data integrity
- Optimizes for primary access patterns
- Follows best practices for chosen database
