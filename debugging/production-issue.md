# Production Issue Investigation

## Incident Details
Severity: [SEV1/SEV2/SEV3]
Started: [DATE_TIME]
Status: [ONGOING/RESOLVED]
Impact: [USER_IMPACT_DESCRIPTION]

## Symptoms
User-facing issues:
- [ISSUE_1]
- [ISSUE_2]

Affected:
- Users: [NUMBER_OR_PERCENTAGE]
- Services: [AFFECTED_SERVICES]
- Regions: [AFFECTED_REGIONS]

## Error Indicators
Monitoring alerts: [ALERTS_TRIGGERED]
Error rate: [ERROR_RATE]
Status codes: [HTTP_STATUS_CODES]

## Logs/Traces
```
[RELEVANT_LOGS_OR_TRACES]
```

## Recent Changes
Deployments in last 24 hours:
- [DEPLOYMENT_1]
- [DEPLOYMENT_2]

Configuration changes:
- [CONFIG_CHANGE_1]

## System State
- CPU: [USAGE]
- Memory: [USAGE]
- Disk: [USAGE]
- Network: [METRICS]
- Database: [CONNECTION_POOL/QUERY_PERFORMANCE]

## Request
Help me investigate and resolve this production issue:

**Immediate Triage:**
1. Assess severity and impact
2. Identify if immediate rollback is needed
3. Determine containment strategies
4. Emergency hotfix requirements

**Investigation Steps:**
1. Where to look first (logs, metrics, traces)
2. What queries to run
3. What commands to execute
4. Which services to check

**Root Cause Analysis:**
1. Timeline of events
2. What triggered the issue
3. Why it happened
4. Why it wasn't detected earlier

**Data to Gather:**
1. Application logs
2. System metrics
3. Database query logs
4. External service status
5. User session data
6. Distributed traces

**Diagnostic Questions:**
1. Is it related to recent deployments?
2. Is it affecting all users or a subset?
3. Is it correlated with traffic patterns?
4. Are there any resource constraints?
5. Are external dependencies healthy?

**Resolution Options:**
1. Immediate mitigation steps
2. Rollback procedures
3. Hotfix approach
4. Configuration changes
5. Traffic routing changes

**Communication:**
1. Status update template
2. User communication
3. Stakeholder notification

**Post-Incident:**
1. Permanent fix strategy
2. Prevention measures
3. Monitoring improvements
4. Post-mortem focus areas

Prioritize quick mitigation over perfect solutions.
