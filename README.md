# Threat Modeling for Web Application (OWASP Threat Dragon)

**Course:** Secure DevOps  
**Task 6:** Data Flow Diagram (DFD) + STRIDE Threat Modeling  
**Student ID:** 21920794  

## Overview
- **Tool:** OWASP Threat Dragon v2.5  
- **Diagram:** WebApp DFD with 3 components, trust boundary, encrypted flows  
- **Threats:** 18 STRIDE threats (6 per component)  
- **Status:** All **Mitigated**  
- **Properties:** Authentication, encryption, credential storage configured  

## Files
- `WebApp Threat Model.json` – Full Threat Dragon model  
- `WebApp Threat Model Report.pdf` – Complete STRIDE report  

## Key Mitigations
- HTTPS + HSTS  
- Parameterized SQL queries  
- TDE + MFA  
- RBAC + audit logs  
- CSP + input validation  
