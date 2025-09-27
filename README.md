# Install-Splunk-Server

<h2>Description</h2>
Project consists of a simple install of Splunk, a SIEM, on an Unbuntu Server. 
<br />


<h2>Objectives</h2>


## Core Objectives (Foundations)

1. **Install and configure Splunk Enterprise (free license)** in a VM and verify ingestion of sample log files.
    
2. **Set up Splunk Forwarders** on other lab machines (Windows & Linux) to centralize log collection.
    
3. **Ingest key log sources**:
    
    - Windows Event Logs (via Universal Forwarder).
        
    - Syslog from Linux or network devices (e.g., a pfSense VM).
        
    - Application logs (e.g., Apache, Nginx, IIS).
        
4. **Learn Splunk Search Processing Language (SPL)** basics: filtering, stats, timechart, and eval commands.
    

---

## Security-Focused Objectives

5. **Simulate security events** in the lab (failed logins, account lockouts, port scans) and detect them in Splunk searches.
    
6. **Build correlation searches** — e.g., multiple failed logins followed by a successful login from the same IP.
    
7. **Install Splunk Security Essentials app** for pre-built use cases and examples.
    
8. **Create dashboards** to monitor:
    
    - Authentication activity.
        
    - Firewall blocks/allow rules.
        
    - Endpoint process starts or PowerShell usage.
        
9. **Test alerting** by configuring email/Slack alerts when certain thresholds are met (e.g., >10 failed logins in 5 minutes).
    

---

## Advanced Objectives

10. **Parse and normalize logs** using Splunk’s **Field Extractions** and **Data Models**.
    
11. **Install & use Threat Intelligence feeds** (open-source threat lists) to enrich your data.
    
12. **Explore Splunk Enterprise Security (ES) Trial** in the lab for hands-on SIEM experience.
    
13. **Baseline “normal” traffic and behavior**, then detect anomalies (e.g., unusual login hours, spikes in DNS queries).
    
14. **Integrate pfBlockerNG or Suricata logs** from your firewall to practice network threat hunting.
    

---

##  Other Goals

15. **Automate ingestion & analysis** with Splunk apps or add-ons (Windows TA, Sysmon TA).
    
16. **Compare Splunk with another SIEM** (like Elastic Security or Wazuh) to see differences in workflow.
    
17. **Document lab findings** like an analyst would — mock up incident reports based on your detections.




<h2>Steps</h2>

