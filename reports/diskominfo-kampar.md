# Security Report - Diskominfo Kampar

## Target
Website resmi Diskominfo Kampar & related government websites

## Vulnerability Type
Broken Link Hijacking (BLH) / Social Media Link Misconfiguration

---

## CWE Reference
CWE-610: Externally Controlled Reference to a Resource in Another Sphere

---

## Description
I found that the official website of Diskominfo Kampar contains a social media (Instagram) link that may lead to an external account which is no longer active or not properly maintained.

This creates a risk where the linked username can potentially be re-registered by another party, which may redirect users to an unintended account.

---

## Steps to Reproduce
1. Visit the official Diskominfo Kampar website  
2. Click on the Instagram / social media link  
3. Observe the redirect behavior  

---

## Impact
- Possible redirection to unintended or impersonated Instagram account  
- Users may trust an unofficial account due to official website linking  
- Risk of social engineering or impersonation  
- Loss of trust in official government digital presence  

---

## Status
Reported to relevant parties but no clear follow-up yet (unresolved)

---

## Notes
This issue has been reported through official channels, but there has been no confirmation or fix status at the time of writing.
