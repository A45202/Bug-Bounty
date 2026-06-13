# Broken Link Hijacking – Diskominfo Salatiga

## Target
https://diskominfo.salatiga.go.id/

## Organization
Diskominfo Kota Salatiga

---

## Vulnerability
Broken Link Hijacking (BLH)

---

## Description
The website contains a social media link pointing to an inactive Twitter / X account username.

This username can be registered again by another user, which may cause the official website link to redirect users to an unintended account.

---

## CWE Reference
CWE-610: Externally Controlled Reference to a Resource in Another Sphere

---

## Severity
Medium

### Reason
- The link is placed on an official government website  
- The target resource is an external Twitter / X account not controlled by the organization  
- The username can be re-registered by another party  
- This may lead to impersonation or social engineering risks  

---

## Steps to Reproduce
1. Open the website  
2. Click the Twitter / X icon/link  
3. Observe that the account username is inactive  
4. The username can be registered again  
5. The link may then redirect to a new account owner  

---

## Impact
- Possible impersonation of official Twitter / X account  
- Social engineering or phishing risk  
- Users may be misled into trusting a non-official account  
- Reduced trust in official communication channels  

---

## Status
Resolved after responsible disclosure. The issue was reported directly to the official government administration team and has since been fixed by updating the affected social media link.
