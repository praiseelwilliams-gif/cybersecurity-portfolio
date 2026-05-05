# Security Incident Analysis – Hotel Data Breach

## Scenario Summary

A global hotel chain experienced a data breach affecting over three million customers. Attackers gained access to the company’s customer database using the login credentials of an employee.

Although no passwords or financial data were reportedly accessed, personal customer information was exposed.

---

## Analysis Using the McCumber Cube

This incident highlights weaknesses across multiple dimensions of the McCumber Cube framework.

---

### 1. Security Principles

 **Confidentiality** was compromised
  Unauthorized individuals gained access to sensitive customer data.

 **Integrity** and **Availability** were not explicitly affected in this case, but could have been at risk.

---

### 2. Data State

* The breach likely affected **data at rest** (customer database).
* Access may also have occurred during **data in use**, depending on how the system was accessed.

---

### 3. Security Controls (Main Weakness)

####  Weakness Identified:

Compromised employee credentials indicate insufficient access control and monitoring.

---

## What Could Have Been Done Better

### 1. Implement Multi-Factor Authentication (MFA)

* Prevents unauthorized access even if login credentials are stolen
* Adds an extra layer of security beyond passwords

---

### 2. Employee Security Awareness Training

* Train staff to recognize phishing emails and social engineering attacks
* Reduce the risk of credential compromise

---

### 3. Strong Access Control (Least Privilege)

* Limit employee access to only the data necessary for their role
* Prevent full database access from a single compromised account

---

### 4. Continuous Monitoring and Logging

* Use SIEM tools to detect unusual login activity
* Identify suspicious behavior (e.g., login from unusual locations)

---

### 5. Endpoint and Identity Security

* Use identity protection tools to detect compromised accounts
* Enforce strong password policies and regular updates

---

### 6. Incident Response Preparedness

* Ensure rapid detection and containment of breaches
* Regularly test incident response plans

---

## Key Takeaway

This breach demonstrates that relying solely on passwords is insufficient. A layered security approach combining technical, administrative, and human-focused controls is essential to protect sensitive data.

Proper implementation of the McCumber Cube principles could have significantly reduced the impact or prevented the breach entirely.

