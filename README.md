# Cybersecurity Lab Writeups

Hands-on cybersecurity lab exercises with a focus on **detection and response (SOC L1 / Blue Team)**.

Each writeup documents an attack executed in a controlled, isolated home lab, then analyzes it from a **defender's perspective** — reconstructing the attack chain, extracting indicators of compromise, mapping to MITRE ATT&CK, and producing concrete detection logic (Suricata/Snort signatures, Wazuh rules, and Wireshark analysis).

> All work in this repository is performed in a personal, network-isolated lab using intentionally vulnerable machines. No production systems, external networks, or third parties are involved.

---

## Writeups

| Writeup | Focus | Key skills demonstrated |
|---|---|---|
| [UnrealIRCd Backdoor — CVE-2010-2075](./unrealircd-cve-2010-2075-writeup.md) | RCE via IRC service backdoor | Traffic analysis, Base64 evasion analysis, detection engineering, MITRE ATT&CK mapping |

---

## Lab environment

| Component | Detail |
|---|---|
| Hypervisor | VMware Workstation Pro |
| Attacker | Kali Linux |
| Targets | Metasploitable2 / Metasploitable3 |
| Analysis & detection | Wireshark, Nmap, Nessus, Metasploit Framework |
| Focus area | Blue Team / SOC Level 1 — detection, IOCs, incident analysis |

---

## About

I'm transitioning into cybersecurity with a focus on **SOC Level 1 / Blue Team** roles. My background includes bilingual (English/Spanish) technical customer support for U.S. clients, which I'm applying to security operations: incident triage, communication, and structured analysis.

This repository is where I document my hands-on lab work as I build detection and response skills.

**LinkedIn:** [linkedin.com/in/gerber-estrada](https://linkedin.com/in/gerber-estrada)
