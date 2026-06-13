# Broken Link Hijacking – Korlantas SIM

## Target
https://digitalkorlantas.polri.go.id/sim/

## Organization
Korlantas Polri

---

## Vulnerability
Broken Link Hijacking (BLH)

---

## Description
The website contains an Instagram link that points to a username which is no longer active.  
This username can be re-registered by another user, which may cause the official website link to redirect to an unintended account.

---

## CWE Reference
CWE-610: Externally Controlled Reference to a Resource in Another Sphere

---

## Severity
Medium

### Reason
- The link is placed on an official and trusted government website  
- The target resource is external and not controlled by the website owner  
- The username can be taken by another party  
- This may lead to impersonation or social engineering risks  

---

## Steps to Reproduce
1. Open the target website  
2. Click the Instagram icon/link  
3. Notice the username is no longer active  
4. The username can be registered again  
5. The link will then redirect to the new account owner  

---

## Impact
- Possible impersonation of an official account  
- Social engineering or phishing risk  
- Users may trust a non-official account  
- Reduced trust in official communication channels  

---

## Status
Fixed after responsible disclosure
