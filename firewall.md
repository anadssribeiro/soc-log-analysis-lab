
<img width="755" height="242" alt="alert_firewall8816" src="https://github.com/user-attachments/assets/527ef2c2-31d9-40e9-baa6-dad1a0dcca1f" />


<img width="950" height="425" alt="image" src="https://github.com/user-attachments/assets/805baa0d-9e17-4106-8312-7ef4f0559214" />


<img width="430" height="293" alt="image" src="https://github.com/user-attachments/assets/d1c633f5-5a1c-4bb5-972e-32c4fab2cc1e" />


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

firewall_alert

Source endpoint activity and related web browsing
<img width="938" height="447" alt="image" src="https://github.com/user-attachments/assets/4f50d2d4-7e09-4b55-b72c-eb4565026023" />

URL reputation analysis using TryDetectThis

url_analysis

## Conclusion

The alert was classified as a True Positive.

Investigation revealed that a Human Resources workstation attempted to access a URL that was present on the organization's blacklist. Firewall logs confirmed that the outbound connection was successfully blocked before communication with the destination host could occur.

Review of related endpoint activity showed legitimate HR-related web searches immediately preceding the event. Additional URL reputation analysis using TryDetectThis classified the destination URL as MALICIOUS, validating the firewall detection.

Although no successful connection or endpoint compromise was observed, the alert accurately identified an attempt to access malicious infrastructure. Based on the available evidence, the alert was classified as a True Positive and the security control was confirmed to be functioning as intended.

## Skills Demonstrated
Firewall alert triage
Network log analysis
Threat intelligence enrichment
URL reputation analysis
True positive determination

Security documentation
