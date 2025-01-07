# Elastic-SIEM-Lab
Elastic Stack Security Information and Event Management (SIEM) using the Elastic Web portal and a Kali Linux VM.

# Description
- Set up and configured Elastic Stack SIEM in a home lab environment. Demonstrated proficiency in deploying a Kali Linux VM, configuring Elastic Agents for log collection, and forwarding data to the SIEM for effective security event monitoring..
- Developed a custom dashboard in Elastic SIEM to visualize security events, demonstrating skills in data interpretation and pattern recognition.
- Acquired hands-on experience in generating and analyzing security events using Nmap on Kali Linux. Proficient in querying Elastic SIEM to identify and investigate security incidents, enhancing skills in network security monitoring and threat detection.

# Key Technologies Used
- Elastic
- Virtual Machine
- Linux

# Steps
1. Setting up the Agent to Collect Logs : An agent is a software program that is installed on a device, such as a server or endpoint, to collect and send data to a centralized system for analysis and monitoring. In the context of Elastic SIEM, an agent is used to collect and forward security-related events from your endpoints to your Elastic SIEM instance.
 ![image](https://github.com/user-attachments/assets/c3037202-59b2-4209-8a59-e38e4eda029f)
2. Generating Security Events on the Kali VM : To verify that the agent is working correctly, you can generate some security-related events on your Kali VM. To do this, we can use a tool like Nmap. Nmap (Network Mapper) is a free and open-source utility used for network exploration, management, and security auditing. It is designed to discover hosts and services on a computer network, thus creating a “map” of the network. Nmap can be used to scan hosts for open ports, determine the operating system and software running on the target system, and gather other information about the network.
![image](https://github.com/user-attachments/assets/2edc1ce9-4f7c-47c9-bc7a-54c365e2b646)
3. Querying for Security Events in the Elastic SIEM : Using queries in Elastic to filter logs for alerts and errors.
4. Create a Dashboard to Visualize the Events
   ![image](https://github.com/user-attachments/assets/15d758ec-e807-4397-b472-a635ff2a47a3)
5. Create an Alert : In a SIEM, alerts are a crucial feature for detecting security incidents and responding to them in a timely manner. Alerts are created based on predefined rules or custom queries, and can be configured to trigger specific actions when certain conditions are met. In this task, we will walk through the steps of creating an alert in the Elastic SIEM instance to detect Nmap scans. By following these steps, you can create an alert that will monitor your logs for Nmap scan events and then notify you when they are detected.

# Conclusion
In conclusion, the Elastic SIEM (Security Information and Event Management) Lab project provided a comprehensive hands-on approach to deploying and utilizing the Elastic Stack (Elasticsearch, Logstash, Kibana, and Beats) for security event monitoring and analysis. By following the setup methodology, we successfully configured the key components of the Elastic Stack, enabling the collection, storage, and visualization of security-related logs.


   

