# SIEM-Based-Threat-Detection-Lab

## Objective

The SIEM-Based-Threat-Detection-Lab project aimed to establish a controlled environment for simulating and detecting cyber attacks. The primary focus was to ingest and analyze logs within a Security Information and Event Management (SIEM) system, generating test telemetry to mimic real-world attack scenarios. This hands-on experience was designed to deepen understanding of network security, attack patterns, and defensive strategies.

### Skills Learned
- Windows Event Log analysis
- Splunk searches, alerts, and dashboards
- Wireshark traffic capture and filtering
- SIEM log collection and analysis
- Network attack simulation and detection
- Advanced understanding of SIEM concepts and practical application.
- Proficiency in analyzing and interpreting network logs.
- Ability to generate and recognize attack signatures and patterns.
- Enhanced knowledge of network protocols and security vulnerabilities.
- Development of critical thinking and problem-solving skills in cybersecurity.

### Tools Used
- Splunk Enterprise
- Splunk Universal Forwarder
- Kali Linux (attacker VM)
- Wireshark (network analysis)
- Windows VM (target)

## Project Structure
- `Steps.md` → Detailed step-by-step instructions with screenshots.  
- `Screenshots/` → Contains images referenced in `Steps.md`.  
- `Splunk_Searches.txt` → Example queries used in the lab.  
- `Wireshark_Filters.txt` → Filters used to capture attack traffic.

---

## Key Event Codes
| Event Code | Description |
|------------|------------|
| 5156 | Allowed connection |
| 5157 | Blocked connection |
| 4625 | Failed login attempts |

---

## How to Use
1. Open **Steps.md** to follow the lab step by step.  
2. Review the screenshots in the `Screenshots/` folder.  
3. Use the example **Splunk queries** in `Splunk_Searches.txt` to reproduce searches.  
4. Apply **Wireshark filters** in `Wireshark_Filters.txt` to replicate traffic capture.

---

## Screenshots Preview
| Screenshot | Description |
|------------|------------|
| 01_Nmap_Scan.png | Nmap scan generating network activity |
| 02_Splunk_Logs.png | Windows Firewall logs collected in Splunk |
| 03_Splunk_Alert.png | Alert setup for repeated blocked connections |
| 04_Splunk_Dashboard.png | Dashboard visualization of attack events |
| 05_Wireshark_Capture.png | TCP SYN packets from attacker VM |
| 06_Firewall_Log.png | Raw firewall logs from Windows VM |
| 07_Failed_Login.png | Failed login attempts detection |
