# 🛡️ ICMP Flood Incident Response Report

An incident response analysis of an ICMP flood Denial-of-Service (DoS) attack, structured using the **NIST Cybersecurity Framework (CSF)**. Completed as part of the Google Cybersecurity Professional Certificate.

## 📖 Project Overview

Documented and analyzed a security incident where the organization's network services became unresponsive due to a flood of ICMP packets. Applied the **NIST Cybersecurity Framework** to structure the response across all five core functions: **Identify, Protect, Detect, Respond, and Recover**.

## 🎯 Incident Summary

The organization's network services suddenly stopped responding due to a flood of incoming ICMP packets. This caused legitimate traffic and requests to fail. The incident management team responded by:

- Blocking incoming ICMP packets
- Stopping non-critical network services
- Restoring critical network services

### 🔍 Root Cause
Investigation revealed the ICMP flood was possible because of an **unconfigured firewall**, which allowed the threat actor to execute a DoS attack unimpeded.

### 🛠️ Remediation Actions Implemented
Following the incident, the network security team put the following controls in place:

- 🚧 A new **firewall rule** to limit the rate of incoming ICMP packets
- 🕵️ **Source IP address verification** on the firewall to detect spoofed IPs
- 📊 **Network monitoring software** to detect abnormal traffic patterns
- 🛡️ An **IDS/IPS system** to filter suspicious ICMP traffic

## 📋 NIST Cybersecurity Framework Analysis

### 🎯 Identify
A malicious actor executed an **ICMP flood attack** against the organization.

- **Impact scope:** The entire internal network was affected
- **Priority:** All critical network resources needed to be secured and restored to normal operations
- **Attack type:** Denial-of-Service (DoS) via ICMP flooding

### 🛡️ Protect
The cybersecurity team implemented preventive controls to reduce the likelihood of future attacks:

- ✅ New firewall rule to **limit incoming ICMP packets**
- ✅ **IDS/IPS system** deployed to filter ICMP traffic based on suspicious characteristics

### 🔎 Detect
Detection capabilities were enhanced to identify future attacks earlier:

- ✅ **Source IP address verification** on the firewall to check for spoofed IPs on incoming ICMP packets
- ✅ **Network monitoring software** deployed to detect abnormal traffic patterns

### 🚨 Respond
If this incident occurs again, the cybersecurity team's response plan includes:

1. 🔒 **Isolate affected systems** to prevent further disruption to the network
2. ⚙️ **Restore critical systems and services** disrupted by the event
3. 📊 **Analyze network logs** for suspicious and abnormal activity
4. 📝 **Report all incidents** to upper management and appropriate personnel

### 🔄 Recover
Recovery from an ICMP flood DoS attack requires restoring services to a normal state:

1. 🛡️ **Block external ICMP flood attacks** at the firewall
2. ⏸️ **Stop non-critical network services** to reduce internal traffic load
3. 🚀 **Restore critical network services** as quickly as possible
4. 🔄 **Bring non-critical services back online** once the flood has stopped

## 🛠️ Tools & Skills Used

- **NIST Cybersecurity Framework** application
- **Incident Response Methodology**
- **Firewall Configuration Analysis**
- **DoS / DDoS Attack Recognition**
- **IDS/IPS Concepts**
- **Network Traffic Analysis**
- **Professional Incident Reporting**

## 💡 Key Concepts Applied

- **ICMP (Internet Control Message Protocol)** — used for diagnostics (e.g., ping); commonly abused in flood attacks
- **DoS (Denial-of-Service) Attack** — overwhelming a system to disrupt its availability
- **IP Spoofing** — forging source IPs to hide attacker identity or bypass filtering
- **IDS/IPS (Intrusion Detection/Prevention Systems)** — automated traffic filtering based on threat signatures
- **Defense in Depth** — layered security across firewall, monitoring, and IDS/IPS

## 🎓 Lessons Learned

- **Misconfigured firewalls** are one of the most common attack vectors — proper configuration is critical
- The **NIST CSF** provides a proven structure for organizing incident response
- **IP verification** is simple but powerful defens against volumetric attacks
- **Detection and response speed** matter as much as prevention — you cannot stop every attack
- **Documentation and reporting** are essential for continuous improvement and compliance

## 📚 Certificate Context

This project was completed as part of the **Google Cybersecurity Professional Certificate** on Coursera, demonstrating practical application of the NIST Cybersecurity Framework and incident response methodology in a simulated enterprise scenario.

## 👤 Author

**Yorgo Albitar**
Cybersecurity Student | Aspiring SOC Analyst
📧 Email: Yorgobitar59@gmail.com
🔗 GitHub: https://github.com/Yorgo-Albitar
