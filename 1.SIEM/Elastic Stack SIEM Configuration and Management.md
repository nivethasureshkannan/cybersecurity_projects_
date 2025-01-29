# Elastic Stack SIEM Configuration and Management
> Elastic SIEM is a Security Information and Event Management (SIEM) product that helps security teams detect and respond to threats. It's built on the open-source Elastic Stack, which includes Elasticsearch, Logstash, and Kibana.

## Project Overview
- Configured **Elastic Stack SIEM** in a home lab using **VirtualBox**.
- Installed **Kali Linux VM** and performed **Nmap scans** to simulate attacks.
- Forwarded logs to **Elastic SIEM** for real-time security monitoring.
- Created **custom dashboards** and **email alerts** for incident detection.

## Tools & Technologies
- **Virtualization:** VirtualBox
- **SIEM Platform:** Elastic Stack (Elasticsearch, Kibana, Logstash, Beats)
- **Security Testing:** Nmap (port scanning, vulnerability detection)
- **Operating Systems:** Kali Linux VM
- **Log Collection:** Elastic Agent  
- **Alerting:** Rule-based alerts with email notifications

## Process walkthrough
* Installed VirtualBox and created Kali Linux VM:
![vbox](https://github.com/nivethasureshkannan/cybersecurity_projects_/blob/main/1.SIEM/assets_1/SIEM_1_vb.png?raw=true)

*Installed and configured Elastic SIEM for log collection in my kali linux VM.
![elastic_siem](https://github.com/nivethasureshkannan/cybersecurity_projects_/blob/main/1.SIEM/assets_1/SIEM_1_1.png?raw=true)

![elastic_siem](https://github.com/nivethasureshkannan/cybersecurity_projects_/blob/main/1.SIEM/assets_1/SIEM_1_2.png?raw=true)

![elastic_siem](https://github.com/nivethasureshkannan/cybersecurity_projects_/blob/main/1.SIEM/assets_1/SIEM_1_3.png?raw=true)

![elastic_siem](https://github.com/nivethasureshkannan/cybersecurity_projects_/blob/main/1.SIEM/assets_1/SIEM_1_4.png?raw=true)

![elastic_siem](https://github.com/nivethasureshkannan/cybersecurity_projects_/blob/main/1.SIEM/assets_1/SIEM_1_5.png?raw=true)

![elastic_siem](https://github.com/nivethasureshkannan/cybersecurity_projects_/blob/main/1.SIEM/assets_1/SIEM_1_6.png?raw=true)

![elastic_siem](https://github.com/nivethasureshkannan/cybersecurity_projects_/blob/main/1.SIEM/assets_1/SIEM_1_7.png?raw=true)

* Performed some basic  Nmap scan to generate logs
![elastic_siem](https://github.com/nivethasureshkannan/cybersecurity_projects_/blob/main/1.SIEM/assets_1/SIEM_1_8.png?raw=true)

* Created Alerts & Configured Email Notifications if any nmap scans are take place
![elastic_siem](https://github.com/nivethasureshkannan/cybersecurity_projects_/blob/main/1.SIEM/assets_1/SIEM_1_rule.png?raw=true)

* Then again ran some nmap scans and monitored the logs
![elastic_siem](https://github.com/nivethasureshkannan/cybersecurity_projects_/blob/main/1.SIEM/assets_1/SIEM_1_9.png?raw=true)

* But this time it has been alerted
![elastic_siem](https://github.com/nivethasureshkannan/cybersecurity_projects_/blob/main/1.SIEM/assets_1/SIEM_1_10.png?raw=true)

* And an email has been sent successfully to the configured mail id.
![elastic_siem](https://github.com/nivethasureshkannan/cybersecurity_projects_/blob/main/1.SIEM/assets_1/SIEM_1_11.png?raw=true)

* A custom dashboard has been created to show the count of events in a host with respect to time.
![elastic_siem](https://github.com/nivethasureshkannan/cybersecurity_projects/blob/main/1.SIEM/assets_1/SIEM_1_12.png?raw=true)

---
> Thank you so much for your time.
