# TryHackMe - Defensive Security Intro

## Room Completed: 27-28 July 2026

### What I Learned

**Offensive Security vs Defensive Security:**
- Offensive Security: Thinking like an attacker to find weaknesses (penetration testing)
- Defensive Security: Protecting systems and detecting attacks (SOC analyst role)

### Role: Security Operations Center (SOC) Analyst

**Responsibilities:**
- Monitor company security dashboards in real-time
- Detect suspicious activities and alerts
- Investigate incidents
- Take action to stop attacks (block IPs, isolate systems)
- Generate incident reports

### Practical Tasks Done

**Task 1: Identify Suspicious Activity**
- Reviewed SOC dashboard with multiple alerts
- Found "Web Discovery Attack" - automated directory enumeration

**Task 2: Identify Attacker's IP**
- Source IP: `32.122.195.63`
- Attack type: Web Discovery (tool like `dirb` being used to find hidden pages)

**Task 3: Implement Security Actions**
- Blocked attacker's IP at firewall level
- Result: "32.122.195.63 is now blocked. All connection attempts will be dropped."
- Completed investigation successfully

### Key Takeaways

- Defenders need to understand attacker tactics to detect them
- Real-time monitoring is crucial in cybersecurity
- Quick response to threats prevents damage
- Tools like SIEM dashboards help visualize security events

### Next Steps

- Learn more about SIEM tools (Splunk, Wazuh)
- Study incident response procedures
- Explore "SOC Level 1" TryHackMe path
