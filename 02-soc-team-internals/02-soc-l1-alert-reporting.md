# SOC L1 Alert Reporting

## Room Link
https://tryhackme.com/room/socl1alertreporting

---

## Objective
Learn how a Tier 1 SOC Analyst documents and reports investigated alerts in a clear and structured way.

---

## Key Concepts

### What is Alert Reporting?
Alert reporting is the process of **documenting the findings of an investigation** after triaging an alert.

This ensures:
- Clear communication between analysts  
- Proper escalation  
- A record for future reference  

✅ Key Idea:  
If it’s not documented, it didn’t happen  

---

### Purpose of Reporting

SOC reporting helps:

- Track security incidents  
- Provide context with other teams  
- Support incident response efforts  
- Maintain accurate records of activity  

---

### Components of a Good Report

A proper SOC alert report should include:

- **Summary** → What happened  
- **Details** → Systems, users, and activity involved  
- **Analysis** → Why it is or isn’t malicious  
- **Classification** → True positive or false positive  
- **Action Taken** → Escalation or closure  

✅ Key Idea:  
Reports should be **clear, concise, and evidence-based**

---

### Writing Like an Analyst

When documenting findings:

- Use objective language (avoid assumptions)  
- Base conclusions on evidence  
- Keep explanations simple and clear  
- Include relevant indicators (IP, user, timestamps)  

✅ Example:
Instead of:  
“this looks suspicious”

Write:  
“Multiple failed login attempts followed by a successful login from a new IP address”

---

### When to Escalate

- The alert is an indicator of a major cyberattack requiring deeper investigation or DFIR
- Remediation actions like malware removal, host isolation, or password reset are required
- Communication with customers, partners, management, or law enforcement agencies is required
- You just do not fully understand the alert and need some help from more senior analysts  

✅ Key Idea:  
Know the scope of your responsibilities and escalate when needed 

---

## What I Learned

- Documentation is a critical part of SOC operations  
- Clear reporting improves team efficiency and communication  
- Reports must be based on evidence, not assumptions  
- Good documentation supports faster and more effective incident response 
- I's better to get clarification on an alert than blindly close it

---

## Screenshots
<img width="608" height="280" alt="image" src="https://github.com/user-attachments/assets/d4ebdf9a-680b-41e2-8e8f-ad597e0af160" />

---

## Tags
SOC Analyst, Alert Reporting, Incident Documentation, Security Operations, Threat Detection, Blue Team, TryHackMe
