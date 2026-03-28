# FUTURE_CS_03
# API Security Risk Analysis

## Overview
This project presents a security assessment of the JSONPlaceholder API to identify common API vulnerabilities related to authentication, authorization, input validation, and security configurations.

---

## Objective
- Evaluate API security posture  
- Identify key vulnerabilities  
- Provide practical security recommendations  

---

## Scope & Methodology
- Public REST API tested using read-only methods  
- Analysis included:
  - Authentication & Authorization  
  - Input Validation  
  - Response Behavior  
  - Security Headers  

---

## Tools Used
- Postman  
- Browser Developer Tools  

---

## Key Findings
- No Authentication Controls — High Risk  
- No Authorization for Data Modification — High Risk  
- Weak Input Validation — Medium Risk  
- Missing Security Headers — Medium Risk  

---

## Risk Summary
**Overall Risk Level: High**

---

## Recommendations
- Implement authentication (API keys, JWT)  
- Enforce access control (RBAC)  
- Validate all inputs  
- Add security headers  
- Apply rate limiting  

---

## Conclusion
The API demonstrates critical security gaps that would pose serious risks in a production environment. Implementing standard security controls is essential to improve overall security.

---

## Files
- `API Security Risk Analysis.pdf`  
- `/Screenshots`  

---

## Author
Elvina Prakash Pillay
