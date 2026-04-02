# FUTURE_CS_03  
Cyber Security Internship – Task 3  
API Security Risk Analysis (Read-Only Assessment)

## Objective  
This project focuses on performing a read-only API security risk analysis of a public test API to identify common API security weaknesses and provide remediation recommendations.

## API Tested   

Endpoints analyzed:
- /users
- /posts
- /posts/{id}

## Tools Used  
- Postman (API testing and request inspection)  
- Browser DevTools (Header inspection)  
- Manual risk assessment  

## Key Findings  

### 1. Open / Unauthenticated Endpoints  
Endpoints accessible without authentication.

### 2. Excessive Data Exposure  
User data exposed without restriction.

### 3. Broken Object Level Authorization (BOLA)  
Objects accessible by modifying ID parameter.

### 4. Missing Rate Limiting  
No visible throttling or request limits.

### 5. Missing Authentication Headers  
No authorization mechanism enforced.

## Risk Summary  
Medium Risks: 4  
Low Risks: 1  

## Conclusion  
The API demonstrates common security weaknesses such as open access, lack of authentication, and missing rate limiting. Implementing proper authentication and authorization controls would significantly improve security posture.

Prepared by: **Mohammed Abdul Majeed**   
Cyber Security Intern – 2026  
