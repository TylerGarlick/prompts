# Production Deployment Checklist

## Application Details
Application: [APP_NAME]
Version: [VERSION]
Release type: [MAJOR/MINOR/PATCH/HOTFIX]

## Pre-Deployment
Current production state:
- Version: [CURRENT_VERSION]
- Known issues: [ISSUES]
- Recent changes: [CHANGES]

Changes in this release:
- [ ] [CHANGE_1]
- [ ] [CHANGE_2]
- [ ] [CHANGE_3]

## Deployment Environment
- Target: [PRODUCTION_ENV]
- Deployment window: [DATE_TIME]
- Expected downtime: [DURATION]

## Request
Create a comprehensive deployment plan including:

**Pre-deployment checklist:**
1. Testing verification (all tests passing)
2. Code review completion
3. Security scan results
4. Performance testing results
5. Database migration scripts ready
6. Rollback plan prepared
7. Monitoring alerts configured
8. Team notifications sent
9. Backup verification

**Deployment steps:**
1. Step-by-step deployment procedure
2. Database migration execution
3. Application deployment
4. Configuration updates
5. Cache clearing/warming
6. Smoke tests to run

**Post-deployment checklist:**
1. Health check verification
2. Monitoring dashboards review
3. Error rate monitoring
4. Performance metrics validation
5. User acceptance testing
6. Documentation updates
7. Team notification

**Rollback plan:**
1. Rollback triggers/criteria
2. Rollback procedure steps
3. Data rollback considerations
4. Communication plan

Include time estimates for each step and responsible parties.
