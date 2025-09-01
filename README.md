# 🛡️ Cybersecurity Home Lab – SIEM & XDR with Wazuh  

This documents my implementation of a **cybersecurity home lab** by setting up a **Security Information and Event Management (SIEM)** and **Extended Detection and Response (XDR)** solution using **Wazuh**.  

The lab was built following a structured tutorial and serves both as a **learning project** and as a **demonstration of hands-on cybersecurity skills** in monitoring, detection, and response.  

---

## 🎯 Project Objectives
- Deploy and configure a modern SIEM/XDR system.  
- Build a cybersecurity home lab environment using **VirtualBox** and **Ubuntu**.  
- Gain hands-on experience with Wazuh components:
  - **Wazuh Manager**
  - **Wazuh Agent**
  - **Wazuh Dashboard**
- Implement **File Integrity Monitoring (FIM)** by modifying Wazuh agent configurations.  
- Explore real-world use cases for **threat detection and response**.  

---

## 🛠️ Tools & Technologies
- **VirtualBox** – Virtualization platform for the lab environment  
- **Ubuntu** – Host OS for running Wazuh components  
- **Wazuh** – Open-source SIEM/XDR solution  
  - Wazuh Manager  
  - Wazuh Agent  
  - Wazuh Dashboard  

---

## ⚙️ Lab Setup
1. **Install VirtualBox** and create virtual machines.  
2. **Deploy Ubuntu Server** as the host OS.  
3. **Install Wazuh Manager** for centralized log collection and rule processing.  
4. **Install Wazuh Agent** on monitored systems.  
5. **Set up Wazuh Dashboard** for real-time monitoring and visualization.  

---

## 🔍 Key Features Implemented
- **Log Collection & Analysis** – Monitor system events from endpoints.  
- **File Integrity Monitoring (FIM)** – Detect unauthorized file changes.  
- **Agent Configuration** – Fine-tune detection capabilities on endpoints.  
- **Security Alerts & Dashboards** – Visualize incidents and responses in Wazuh UI.  

---

## 📊 Example Use Cases
- Detect suspicious file modifications in system directories.  
- Monitor login attempts for signs of brute-force activity.  
- Create alerts for policy violations or unauthorized changes.  

---

## 🚀 Future Enhancements
- Add more agents (Windows + Linux) to simulate enterprise environments.  
- Integrate with **ELK Stack** (Elasticsearch, Logstash, Kibana) for extended analytics.  
- Explore integration with **threat intelligence feeds**.  
- Automate incident response workflows.  

---

## 👨‍💻 Author
**George Abaidoo**  
- 🎓 MSc in Cybersecurity  
- 🔒 Interests: Cybersecurity, AI, Software Development  

