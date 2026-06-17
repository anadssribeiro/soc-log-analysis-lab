
<img width="755" height="242" alt="alert_firewall8816" src="https://github.com/user-attachments/assets/527ef2c2-31d9-40e9-baa6-dad1a0dcca1f" />

- Alert Name: Access to Blacklisted External URL Blocked by Firewall
- Severity: High
- Time of Activity: 06/17/2026 13:07:42 UTC

Related Entities
- Source IP: 10.20.2.17
- Department: Human Resources
- Destination IP: 67.199.248.11
- URL: http://bit.ly/3sHkX3da12340
- Application: web-browsing
- Firewall Rule: Blocked Websites

## Evidence Reviewed
- Firewall alert details

Source endpoint activity and related web browsing
<img width="938" height="447" alt="image" src="https://github.com/user-attachments/assets/4f50d2d4-7e09-4b55-b72c-eb4565026023" />

URL reputation analysis using TryDetectThis

<img width="430" height="293" alt="image" src="https://github.com/user-attachments/assets/d1c633f5-5a1c-4bb5-972e-32c4fab2cc1e" />

## Conclusion
The alert was classified as a True Positive.
The investigation showed that a workstation belonging to the Human Resources department attempted to access a URL that had already been blacklisted by the organization. Firewall logs confirmed that the connection was blocked, preventing any communication with the destination.
Reviewing the user's activity showed legitimate HR-related web searches immediately before the alert was triggered. To better understand the risk, I analyzed the URL using TryDetectThis, which classified it as MALICIOUS.
While there was no evidence that the connection was successful or that the endpoint was compromised, the alert correctly identified an attempt to access malicious infrastructure. Based on the available evidence, I classified the alert as a True Positive.

## Skills Demonstrated
- Firewall alert triage
- Network log analysis
- Threat intelligence enrichment
- URL reputation analysis
- True positive determination
- Security documentation
