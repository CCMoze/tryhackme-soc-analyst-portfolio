# SOC L1 Alert Triage

## Room Link
https://tryhackme.com/room/socl1alerttriage

---

## Objective
Understand how a Tier 1 SOC Analyst investigates and triages security alerts to determine whether they represent real threats.

---

## Key Concepts

### What is Alert Triage?
Alert triage is the process of reviewing and analyzing security alerts to determine:

- Is this a real threat?  
- Is it a false positive?  
- Does it need escalation?  

✅ Key Idea:  
The primary role of an L1 analyst is to **quickly and accurately classify alerts**

---

### Alert Sources

Alerts can come from multiple security tools:

- SIEM platforms  
- EDR solutions  
- Firewalls / IDS  

Each alert provides data such as:
- Source IP  
- Destination  
- User account  
- Activity details  

---

### Triage Process

A typical alert investigation follows these steps:

1. **Review the alert details**
   - What triggered it?
   - Which system/user is involved?

2. **Gather context**
   - Check logs and related events  
   - Look for unusual patterns  

3. **Analyze indicators**
   - Suspicious IPs  
   - Failed login attempts  
   - Unusual behavior  

4. **Determine classification**
   - ✅ True Positive (real threat)  
   - ❌ False Positive (benign activity)  

5. **Take action**
   - Escalate if necessary  
   - Document findings  

✅ Key Idea:  
Context is critical—alerts alone don’t tell the full story  

---

### Common Alert Types

Examples of alerts a SOC analyst may handle:

- Multiple failed login attempts  
- Suspicious IP connections  
- Malware detections  
- Unusual user behavior  

---

### True Positive vs False Positive

#### True Positive
- Confirmed malicious activity  
- Requires escalation or response  

#### False Positive
- Legitimate activity incorrectly flagged  
- No action needed beyond documentation  

✅ Key Idea:  
Reducing false positives improves SOC efficiency  

---

### Analyst Responsibilities

As an L1 SOC Analyst:

- Monitor incoming alerts  
- Perform initial investigation  
- Escalate complex cases  
- Document all findings clearly  

✅ Key Idea:  
Accuracy is more important than speed, but both matter  

---

## What I Learned

- Alert triage is a structured investigation process  
- Context and log correlation are essential  
- Not all alerts indicate real threats  
- Proper classification helps prioritize response efforts  

---

## Screenshots

<img width="900" height="500" alt="image" src="https://github.com/user-attachments/assets/ae047aac-f325-4dda-b823-4d963c008da2" />

---

## Tags
SOC Analyst, Alert Triage, SIEM, Incident Response, Threat Detection, Blue Team, Log Analysis, TryHackMe
