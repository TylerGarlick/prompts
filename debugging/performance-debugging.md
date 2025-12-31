# Performance Debugging

## Performance Issue
System: [SYSTEM_NAME]
Component: [COMPONENT]

## Problem Description
Issue: [PERFORMANCE_ISSUE]
When it occurs: [TIMING/CONDITIONS]
Impact: [USER_IMPACT]

## Performance Metrics
Current:
- Response time: [TIME]
- Throughput: [RATE]
- Resource usage: [CPU/MEMORY/etc.]
- Error rate: [RATE]

Expected:
- Response time: [TARGET]
- Throughput: [TARGET]
- Resource usage: [TARGET]

## Environment
- Load: [CONCURRENT_USERS/REQUESTS]
- Data size: [DATA_VOLUME]
- Infrastructure: [INFRASTRUCTURE_DETAILS]

## Code Context
```[LANGUAGE]
[SUSPECTED_CODE]
```

## Profiling Data
[PROFILING_RESULTS_IF_AVAILABLE]

## Request
Help me diagnose and fix this performance issue:

**Initial Analysis:**
1. Analyze the performance characteristics
2. Identify likely bottlenecks
3. Suggest profiling tools to use
4. Recommend monitoring points

**Profiling Strategy:**
1. CPU profiling approach
2. Memory profiling approach
3. I/O profiling approach
4. Database query profiling
5. Network profiling

**Data Collection:**
What metrics to collect:
1. Response time breakdown
2. Resource utilization over time
3. Database query execution times
4. Cache hit/miss rates
5. Thread/connection pool usage

**Investigation Areas:**
1. Algorithm complexity issues
2. Database query problems (N+1, missing indexes)
3. Memory leaks
4. Inefficient loops
5. Unnecessary I/O operations
6. Blocking operations
7. Resource contention
8. Poor caching strategy

**Root Cause Analysis:**
1. Bottleneck identification
2. Why it's slow
3. What's consuming resources
4. Scaling limitations

**Optimization Recommendations:**
1. Quick wins (low effort, high impact)
2. Code optimizations
3. Configuration changes
4. Infrastructure improvements
5. Architectural changes if needed

**Validation:**
1. How to measure improvement
2. Load testing approach
3. Monitoring to set up

Provide specific, actionable recommendations with expected impact.
