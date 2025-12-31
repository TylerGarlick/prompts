# Performance Review

## Code Context
Component: [COMPONENT_NAME]
Language: [LANGUAGE]
Expected load: [LOAD_DESCRIPTION]

## Code to Review
```[LANGUAGE]
[CODE_TO_REVIEW]
```

## Performance Requirements
- Response time target: [TIME]
- Throughput target: [REQUESTS_PER_SECOND]
- Resource constraints: [CONSTRAINTS]
- Scalability needs: [SCALE_REQUIREMENTS]

## Current Performance
- Current metrics: [METRICS]
- Known issues: [ISSUES]
- Profiling data: [PROFILING_RESULTS]

## Request
Analyze this code for performance issues and optimization opportunities:

**Algorithm Analysis:**
1. Time complexity evaluation
2. Space complexity evaluation
3. Algorithm choice appropriateness
4. More efficient alternatives

**Data Structures:**
1. Appropriate data structure usage
2. Memory efficiency
3. Access patterns optimization

**Database Interactions:**
1. Query efficiency
2. N+1 query problems
3. Proper indexing
4. Connection pooling
5. Batch operations vs individual queries
6. Caching opportunities

**I/O Operations:**
1. File I/O optimization
2. Network I/O efficiency
3. Asynchronous operations usage
4. Buffering strategies

**Memory Management:**
1. Memory leaks
2. Object creation overhead
3. Garbage collection impact
4. Buffer sizing

**Concurrency:**
1. Parallel processing opportunities
2. Thread safety
3. Lock contention
4. Async/await usage

**Caching:**
1. Caching opportunities
2. Cache invalidation strategy
3. Cache hit ratio optimization

**Other Optimizations:**
1. Lazy loading vs eager loading
2. Pagination for large datasets
3. Resource pooling
4. Connection reuse
5. Compression opportunities

Provide:
- Specific bottlenecks identified
- Impact assessment (high/medium/low)
- Optimization recommendations
- Code examples for improvements
- Trade-offs to consider
