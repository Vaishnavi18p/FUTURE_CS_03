#  API Security Risk Analysis Report

This project presents a security analysis of a public API to identify potential risks, evaluate authentication mechanisms, and suggest remediation strategies.



##  Objective

The objective of this project is to:

- Analyze a public API endpoint
- Identify common API security risks
- Evaluate authentication and data exposure
- Classify risk severity (Low / Medium / High)
- Provide remediation suggestions



##  API Tested

- JSONPlaceholder API  
- Endpoint used:  
  https://jsonplaceholder.typicode.com/users



##  Tools Used

- **Postman** – for sending API requests and analyzing responses  
- **Browser DevTools** – for inspecting network requests, headers, and response data  



##  Scope

- Public API testing only  
- Read-only requests (GET method)  
- No exploitation or attack attempts  
- Ethical and safe analysis  



##  Methodology

The following steps were followed during analysis:

1. Selected a public API (JSONPlaceholder)  
2. Sent GET request using Postman  
3. Inspected API response data  
4. Analyzed request and headers using Browser DevTools  
5. Checked for authentication requirements  
6. Identified security risks (authentication & data exposure)  
7. Classified risk severity  
8. Suggested remediation measures  



##  Identified Risks

- **No Authentication (High)**  
  The API allows unrestricted access to user data without authentication.

- **Excessive Data Exposure (High)**  
  The API exposes detailed user information such as email, phone number, and address.



##  Business Impact

- Risk of unauthorized data access  
- Possibility of phishing and identity theft  
- Loss of user trust and reputational damage  
- Potential legal and compliance issues  



##  Remediation Suggestions

- Implement authentication (API keys / OAuth)  
- Restrict access to sensitive endpoints  
- Apply data minimization  
- Enable rate limiting  
- Monitor API usage and logs  



##  Repository Contents

- `API_Security_Report.pdf` → Final report  
- `screenshots/` → Evidence from Postman and DevTools  


##  Key Learning

This project demonstrates how insecure APIs can expose sensitive data and highlights the importance of authentication, access control, and secure API design.



##  Conclusion

API security is essential in modern applications. Proper authentication and controlled data exposure can significantly reduce risks and improve system security.
