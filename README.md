# Future_Interns_Task_03
# API Security Risk Assessment (FUTURE_CS_03)

## Author
Furrell Jordan Meas  
Email: furrelljordanmeas@gmail.com 
Phone: 060 695 9079
---

## Project Overview
This project focuses on assessing the security posture of a publicly accessible REST API (JSONPlaceholder). The objective was to identify common API vulnerabilities using manual testing techniques and align findings with the OWASP API Security Top 10 (2023).

---

## API Overview
The API provides multiple endpoints including:
- `/users`
- `/posts`
- `/comments`
- `/albums`
- `/photos`
- `/todos`

All endpoints were publicly accessible and supported full CRUD operations without authentication or authorization controls.

---

## Tools Used
- Insomnia (API testing)
- Browser Developer Tools (network inspection)
- Web browser (endpoint verification)

---

## User Awareness
This assessment highlights critical security risks that users and developers should be aware of:
- APIs without authentication expose sensitive data
- Lack of authorization allows unauthorized access and modification
- Excessive data exposure increases risk of phishing and data abuse
- Poor API management increases attack surface

---

## Risk Rating Summary
- **High Risk**
  - Broken Object Level Authorization (BOLA)
  - Broken Function Level Authorization  

- **Medium Risk**
  - Broken Object Property Level Authorization  

- **Low Risk**
  - Improper Inventory Management  

---

## Conclusion
The API demonstrates significant security weaknesses due to missing access controls. Immediate implementation of authentication, authorization, and proper API governance is required to mitigate risks.
