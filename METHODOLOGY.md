# Testing Methodology

## 1. Planning

Define the testing scope, target systems, permissions, and testing objectives.

## 2. Reconnaissance

Collect basic information about the authorized staging application, including available pages, forms, and APIs.

## 3. Automated Scanning

Use **OWASP ZAP** or **Burp Suite** to identify potential security issues.

## 4. Manual Testing

Manually review authorized areas such as:

* Login pages
* User profiles
* Input forms
* APIs
* Session management

## 5. Vulnerability Testing

Check for common vulnerabilities including:

* SQL Injection
* Cross-Site Scripting (XSS)
* Cross-Site Request Forgery (CSRF)
* Authentication weaknesses
* Session security issues

## 6. Verification

Review scanner results and safely verify potential findings without damaging systems or accessing unauthorized data.

## 7. Documentation

Record verified findings, severity, affected area, evidence, and recommended security controls.

## 8. Reporting

Prepare the final security report with findings and remediation recommendations.

## 9. Safety

All testing must remain within the authorized scope. No destructive actions, data theft, or unauthorized access should be performed.
