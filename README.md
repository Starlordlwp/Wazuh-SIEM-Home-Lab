# Wazuh-SIEM-Home-Lab

##  Project Overview
This project demonstrates the deployment of an enterprise-grade Open-Source SIEM system using **Wazuh**. The lab consists of a Kali OS laptop hosting the centralized Wazuh Manager hosting the indexer and dashboard, alongside an Ubuntu OS Mac desktop with the remote endpoint running a lightweight Wazuh Agent for active security monitoring and log aggregation.

##  Architecture & Topology
* **SIEM Server (Manager, Indexer, Dashboard):** Kali Linux (`10.0.0.211`) running Wazuh v4.13.1
* **Monitored Endpoint (Agent):** Ubuntu (`OldMac`) running Wazuh Agent v4.13.1

##  Deployment Steps

### 1. Centralized Server Installation
The Wazuh server stack was deployed natively on a Kali Linux environment using the automated all-in-one installation assistant:

"curl -sO [https://packages.wazuh.com/4.13/wazuh-install.sh](https://packages.wazuh.com/4.13/wazuh-install.sh)"
"sudo bash wazuh-install.sh -a" 



   
