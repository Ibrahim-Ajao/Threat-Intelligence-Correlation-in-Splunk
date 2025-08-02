# 🕵️ Threat Intelligence Correlation in Splunk

This project demonstrates how to ingest and correlate external threat intelligence (IOCs) with endpoint logs using Splunk and Sysmon.

## 🎯 Project Goals

- Understand threat intel feeds
- Build lookup-based correlation in Splunk
- Detect malicious IPs and domains in logs
- Create alerts and dashboards for IOC matches

## 📁 Contents

- `threat_intel.csv`: IOC sample feed
- `splunk_queries/`: SPL queries used for detection
- `alerts/`: Alert logic and config
- `reports/`: Summary of IOC matches
- `dashboards/`: Dashboard screenshots

## 📊 IOC Types Used

- Malicious IPs
- Phishing domains
- Suspicious URLs

## 📈 Outcome

Alerts trigger when known IOCs are found in process or network logs. Analysts can visualize IOC matches via dashboards for better triage.

---

Author: Ajao Ibrahim Adewale  
Trainee SOC Analyst  
Google Cybersecurity Certificate Graduate  
