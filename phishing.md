
<img width="761" height="201" alt="initial_alert8814" src="https://github.com/user-attachments/assets/404e4d6e-d467-402d-96c5-6452a01ee4b7" />

- Alert Name: Phishing Analysis
- Severity: Medium
- Time of Activity: 06/17/2026 13:03:15 UTC

Related Entities:
- User: j.garcia@thetrydaily.thm
- Sender: onboarding@hrconnex.thm
- Domain: hrconnex.thm
- URL: https://hrconnex.thm/onboarding/15400654060/j.garcia
- Internal Contact: h.harris@thetrydaily.thm

## Evidence Reviewed

- Email content and sender details
- Embedded URL analysis

- Internal business communications

<img width="812" height="152" alt="splunk_data" src="https://github.com/user-attachments/assets/6a7d4b44-de94-45f7-a057-76af7b839aa9" />

- URL reputation check using TryDetectThis

<img width="428" height="300" alt="third_party_vendor_analysis" src="https://github.com/user-attachments/assets/d9c32354-53e1-4815-8d33-672faa74b259" />


## Conclusion

- The alert was classified as a False Positive.
Investigation revealed that the email was a legitimate onboarding communication from HRConnex, an approved third-party HR provider. Internal HR correspondence confirmed that the recipient was a new employee expected to receive onboarding documentation from this particular vendor.
Additional analysis showed that the sender domain matched the embedded URL domain, and URL reputation checks via TryDetectThis did not find any indicators of phishing or malicious activity.
Based on the available evidence, no security threat was identified and the alert was closed as a False Positive.

## Skills Demonstrated
- Email analysis
- Alert triage
- Threat intelligence enrichment
- URL reputation analysis
- False positive determination
- Security documentation
