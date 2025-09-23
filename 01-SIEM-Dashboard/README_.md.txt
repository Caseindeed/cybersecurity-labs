# 🛡 SOC Project – Windows Sysmon Detection Dashboard

This project demonstrates the design and implementation of a Security Operations Center (SOC) dashboard using **Splunk** and **Sysmon** logs.  
It provides detections across the **MITRE ATT&CK** tactics of Execution, Persistence, Defense Evasion, and Command & Control.

---

## 📄 Project Report
- [SOC_Project_Report.pdf](./SOC_Project_Report.pdf)  
  The main report explaining each detection panel, what it catches, and why it matters.

---

## 📸 Dashboard Screenshots
Each screenshot corresponds to a panel described in the report.

- `DET1_Encoded_PowerShell.png`
- `DET2_Interpreter_Usage.png`
- `DET3_Suspicious_DNS_Queries.png`
- `DET4b_Suspicious_File_Creation.png`
- `DET5_Registry_Persistence.png`
- `DET6a_Event_Log_Clearing.png`
- `DET6b_Suspicious_PS_Evasion.png`
- `Sysmon_Event_Codes.png`
- `Outbound_Connections.png`

---

## 🧩 Dashboard Coverage
- **Execution:** DET1, DET2  
- **Persistence:** DET4b, DET5  
- **Defense Evasion:** DET6a, DET6b  
- **Command & Control:** DET3, Outbound Connections  
- **Context:** Sysmon Event Codes  

---

## 🚀 How to Use
1. Import the Sysmon configuration on a Windows VM.  
2. Ingest logs into Splunk.  
3. Import the dashboard XML panels.  
4. Switch the time range as needed and monitor for detections.  

---

## 🎯 Purpose
This project is designed for **portfolio demonstration** and shows hands-on ability in:
- Detection Engineering  
- SOC Monitoring & Analysis  
- MITRE ATT&CK mapping  
- Splunk dashboard development
