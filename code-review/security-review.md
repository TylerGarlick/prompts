# Security Review

## Code Context
Component: [COMPONENT_NAME]
Type: [WEB_APP/API/LIBRARY/etc.]
Language: [LANGUAGE]

## Code to Review
```[LANGUAGE]
[CODE_TO_REVIEW]
```

## Functionality
This code handles: [DESCRIPTION]
Sensitive data involved: [DATA_TYPES]
User input sources: [INPUT_SOURCES]

## Security Concerns
Known risks: [KNOWN_RISKS]
Compliance requirements: [COMPLIANCE_NEEDS]

## Request
Perform a comprehensive security review covering:

**Input Validation:**
1. All user inputs validated
2. Type checking
3. Length/size restrictions
4. Whitelist vs blacklist approach
5. Encoding validation

**Injection Vulnerabilities:**
1. SQL injection prevention
2. NoSQL injection prevention
3. Command injection prevention
4. LDAP injection prevention
5. XML/XXE injection prevention

**Cross-Site Issues:**
1. XSS (Cross-Site Scripting) prevention
2. CSRF (Cross-Site Request Forgery) protection
3. Clickjacking protection

**Authentication & Authorization:**
1. Authentication mechanism security
2. Password handling (hashing, salting)
3. Session management
4. Token security (JWT, OAuth)
5. Authorization checks
6. Privilege escalation risks

**Data Protection:**
1. Sensitive data encryption (at rest and in transit)
2. Secure communication (HTTPS, TLS)
3. Data exposure risks
4. Logging sensitive information

**Configuration & Dependencies:**
1. Hardcoded secrets/credentials
2. Insecure defaults
3. Vulnerable dependencies
4. Unnecessary permissions

**Error Handling:**
1. Information disclosure in errors
2. Proper exception handling
3. Logging security events

**Other Security Aspects:**
1. Race conditions
2. Resource exhaustion/DoS
3. File upload security
4. API rate limiting
5. CORS configuration

Provide:
- Specific vulnerabilities found
- Severity rating (Critical/High/Medium/Low)
- Remediation recommendations
- Code examples for fixes
