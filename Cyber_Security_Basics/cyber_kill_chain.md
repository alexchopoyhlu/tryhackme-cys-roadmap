## Cyber Kill Chain

The Cyber Kill Chain is a model developed by Lockheed Martin to describe the stages of a cyber attack. It helps defenders understand, detect, and disrupt attacks at each phase. By analyzing adversary behavior across this chain, organizations can build stronger defenses.

---

### Stages of the Cyber Kill Chain

1. **Reconnaissance**  
   The attacker gathers information about the target through passive (e.g., open-source intelligence) or active means (e.g., scanning). This phase sets the foundation for the attack.

2. **Weaponization**  
   The attacker creates a payload (e.g., malware) and couples it with a delivery mechanism (e.g., malicious document, exploit).

3. **Delivery**  
   The weapon is transmitted to the target — commonly via phishing emails, infected websites, or USB drives.

4. **Exploitation**  
   Once delivered, the attacker takes advantage of a vulnerability to execute code or gain access. This step turns the malicious payload into action.

5. **Installation**  
   The attacker establishes a foothold by installing backdoors, remote access tools, or other persistent mechanisms on the target system.

6. **Command and Control (C2)**  
   The compromised system connects to the attacker's server to receive instructions and exfiltrate data. This allows the attacker to maintain control remotely.

7. **Actions on Objectives**  
   The attacker executes the goal of the operation — such as data theft, encryption (ransomware), or system disruption.

---

### Defensive Insight

Understanding the Cyber Kill Chain helps security professionals:

- Detect attacks earlier in the lifecycle.
- Implement targeted controls at each stage (e.g., email filtering for Delivery, EDR for Exploitation).
- Improve incident response and threat hunting.

---
